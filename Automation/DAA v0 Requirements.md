# DAA v0 Requirements (决策辅助 + 可复盘)

来源：`/Users/onekey01/.openclaw/workspace/docs/daa/requirements-v0.md`
同步时间：2026-02-14

---

# DAA v0 需求文档（决策辅助 + 可复盘；AI 可产出建议单，但需二次确认，不自动执行）

更新时间：2026-02-14

## 1. 项目目的（Why）
DAA（Dynamic Asset Allocation）的 v0 目标是做一套“可复盘的决策辅助流水线”。

给定：
- 标的与价格历史（历史行情）
- 市场信息（主观：Twitter；客观：yfinance/雪球）
- 资金约束（比例分配、分类 tag、max in/out 等）
- 人因模型（人的偏好与可信度权重）
- 当前组合状态（持仓/现金/上次再平衡信息）

产出：
- `targetWeights`：目标权重
- `orders`：买卖建议单（建议，不自动执行）
- `explain/warnings`：可追溯解释与风险提示
- `bundle JSON`：一键导出（用于复制、保存、导入恢复、分享、回放对比）

### 成功标准（v0）
- 同一份 `bundle` + 同一套规则，得到的 Step4 输出应可复算（尽可能 deterministic）。
- 不接入实盘自动执行；系统不直接连券商/交易所下单。
- 允许“二次确认 → 记录执行结果”的流程：AI/基准算法可以输出 orders 作为建议单，但必须由用户确认后才进入“已确认/已执行”日志。
- Dashboard 必须能复盘：历史回测结果、当前资金/仓位占比、每次 run 的输入/输出、AI 分析文本，以及（确认/执行）记录。

## 2. 范围（Scope）
### In-scope（v0 必须有）
- Step1 回测算法组合（历史回测、策略评分、组合权重建议）
- Step2 市场信息归一化（Twitter 主观 + yfinance/雪球 客观，统一为 MarketEvent）
- Step3 金额管理系统（比例分配、分类 tag、max in/out）
- Step4 基于基准算法的买入卖出推荐（核心 deterministic 引擎）
- Step5 AI 分析（仅分析、不自动下单；可输出“建议单草稿”供二次确认）
- Step6 人因模型（偏好 + 可信度权重 + explain）
- Step7 导出/导入/复盘（bundle export/import + run log + confirm/executed log）

### Out-of-scope（v0 不做/明确不承诺）
- 无人值守实盘自动下单
- 交易所/券商账户下单撮合、成交回报、清算对账闭环
- 多账户/多用户权限系统（默认单操作者本地使用）

## 3. 核心原则（Principles）
- 单一事实源（SoT）：以 `bundle JSON` 为中心，所有步骤的关键输入/输出都可被导出与回放。
- 可解释：每一步输出都要能说明“基于哪些输入得出哪些结论”。
- 可操作：Step4/Step5 的建议单必须受 Step3 约束约束（max in/out、比例分配、仓位上限等），避免不可执行建议。
- 人在回路（Human-in-the-loop）：所有 orders 都是“建议 → 确认 →（手动执行后）记录”。
- 安全默认：任何涉及密钥/账户信息的接口默认不对公网开放；日志中不得泄露 token。

## 4. 端到端用户流程（Happy Path）
1) 在主入口（建议：`/daa/market/funds` 或 `/daa/dashboard`）看到 DAA Workflow 状态面板
2) Step1：选择 symbol + 日期范围 + 数据源，跑回测得到策略指标与组合权重
3) Step2：导入/抓取市场信息，得到 MarketEvent[]
4) Step3：配置资金与约束（比例、tag、max in/out）
5) Step6：配置人因 profile（risk_preference + skill_score）
6) Step4：生成“基准推荐”（orders + targetWeights + explain + warnings）
7) Step5（可选）：AI 基于 Step4 + 市场信息输出“解释/备选方案/风险提示”，并可给出 `ai_orders_draft`（建议单草稿）
8) 用户选择执行方案：选 Step4 的基准建议单，或选 Step5 的 AI 建议单草稿 → 点击“确认”（Confirm）
9) 用户在外部实际执行（自己操作下单）后，回到 Dashboard 点“标记已执行”（Executed）。系统按确认的 orders 自动更新 portfolio_state（可选：手动覆盖）。
10) Export：一键导出 bundle（包含本次分析与确认/执行记录）；必要时可 Import 恢复状态

## 5. 数据模型（Contracts / SoT）
### 5.1 Bundle（导出/导入的核心对象）
- 必须包含 `schemaVersion` 与 `generatedAt`
- 推荐包含以下字段（按 v0 需要）：
  - `step1_backtest`
  - `step2_market_events`
  - `step3_money_plan`
  - `step4_rebalance_recommendation`
  - `step5_ai_analysis`（可选）
  - `step6_human_profile`
  - `step7_taxonomy`
  - `portfolio_state`（positions/cash/lastRebalance 等）
  - `rebalance_log`（推荐生成记录）
  - `confirm_log`（用户确认记录：确认了哪一套 orders）
  - `execution_log`（用户执行记录：手动执行后的回写）

导入（Import）规则：
- Import 只恢复本地状态（localStorage），不得自动触发外部 API。
- 版本不兼容/字段缺失必须给出可读错误提示（禁止 silent fail）。

### 5.2 Step2 MarketEvent（统一事件）
每条事件建议包含：
- `id`（可选，去重用）
- `source`（twitter | yfinance | xueqiu | manual）
- `at`（时间戳或 YYYY-MM-DD）
- `title/summary`（文本）
- `url`（可追溯链接）
- `symbols`（可选：事件涉及标的）
- `tags`（可选：事件分类）

### 5.3 Step3 Money Plan（资金约束）
必须支持：
- 比例分配（例如：资产类别/组合桶的权重）
- 分类 tag（用于分桶与约束引用）
- max in / max out（单次或周期上限，避免过度换手）
- 最小交易额（min notional，可选但建议）

输出给 Step4/5：
- 可计算的约束对象（不是纯文本说明）。

### 5.4 Step6 Human Profile（人因模型）
你当前的 tag 体系（v0）：
- `risk_preference`: 高 | 中 | 低
- `skill_score`: 高 | 中 | 低 | 傻逼

建议在内部映射为：
- `risk_preference_weight`（影响风险敞口/波动容忍度）
- `trust_weight`（影响建议的激进程度或对某些信号/策略的折扣）

输出必须包含 `explain`，说明权重来源与影响。

### 5.5 Step4 Recommendation（基准推荐输出）
必须输出：
- `orders[]`：至少包含 symbol、side(BUY/SELL)、notional/qty、理由（可简版）
- `targetWeights`：目标权重（总和=1 或明确现金权重）
- `constraintsApplied`：本次使用了哪些约束（max in/out、max position、money plan 等）
- `warnings[]`：例如数据缺失、信号不一致、资金不足、触发阈值未到等
- `explain`：核心解释文本（可多段）

### 5.6 Step5 AI Analysis（仅分析、不自动下单；可输出建议单草稿）
硬性约束（必须写进产品与输出）：
- AI 输出可包含 `ai_orders_draft[]`（结构与 Step4 orders 保持一致或可转换），用于“二次确认”。
- AI 不得自动执行；且 UI 必须强提示："AI 输出仅供参考，不构成投资建议；需人工确认与自行下单"。
- AI 必须引用可追溯输入（MarketEvent/Step4 输出/约束），避免凭空捏造。
- AI 建议单必须过同一套约束校验（max in/out、最小交易额、仓位上限等），否则只能输出为 warnings/讨论项。

### 5.7 Confirm / Execution Log（确认/执行记录）
为满足“你二次确认→自己下单→回写复盘”，需要两类记录：
- `confirm_log[]`：记录用户确认了哪一套 orders（来源=baseline 或 ai），确认时间、确认备注、确认时的输入摘要
- `execution_log[]`：记录用户实际执行后的回写（executedAt、备注）。v0 默认按“确认单=已执行”处理，不强制录入成交价/手续费。
- `portfolio_state` 更新：支持基于“初始仓位 + 已确认 orders”自动更新（假设 100% 成交，使用一份 reference price snapshot 把 notional 转 qty 并更新 cash/positions）。同时保留手动覆盖入口（当真实成交价偏离较大时可修正）。

## 6. 功能需求（按步骤）
### Step1 回测算法组合
- 支持历史价格数据源：
  - 非 crypto：yfinance（日线）
  - crypto：OKX public candles（日线）
- 支持策略集合 v0：至少包含 buy&hold + SMA crossover；后续可扩展
- 输出指标：收益、回撤、夏普、胜率（以及你们已有的评分权重）
- 产出：ranked results + recommended ensemble weights config
- Write-back：结果写入本地 SoT（供 Funds hub/Dashboard 摘要引用）

### Step2 市场信息（主观+客观统一）
- Twitter：支持消息组/用户时间线/搜索等输入方式（以你们已实现为准）
- yfinance/雪球：支持抓取/导入为事件
- 事件 merge + 去重 + cursor 分页（可选）
- 一键 Copy JSON（MarketEvent[]）

### Step3 金额管理系统
- 配置：总资金/可用资金、比例分配、分类 tag、max in/out
- 校验：比例和约束合法性（例如总和、上限/下限）
- 输出：money_plan JSON，一键 Copy

### Step4 基准算法买卖推荐（核心）
输入：
- Step1 backtest/weights config（策略组合/信号参数）
- Step2 MarketEvent[]（解释/校验材料）
- Step3 money_plan（硬约束）
- 当前持仓/现金（portfolio_state）
- 人因模型（Step6）

行为：
- 生成 targetWeights 与 orders
- 严格遵守 max in/out、max position 等约束
- 给出 explain + warnings（例如“触发策略未满足，则不建议交易”）

输出：
- recommendation JSON，一键 Copy
- 可记录到 rebalance log（用于复盘/导出）

### Step5 AI 分析（仅分析、不自动执行；可输出建议单草稿）
- 输入：Step4 recommendation + Step2 events + Step6 profile + Step3 money_plan
- 输出：解释与备选方案 + 风险提示 +（可选）ai_orders_draft
- UI 必须明确标注："仅分析，不自动下单；需人工确认"。

### Step6 人因模型
- 提供 UI 选择：risk_preference、skill_score（含“傻逼”枚举）
- 输出 profile + explain

### Step7 导出/导入/复盘
- Export：一键打包 Step1/2/3/4/5/6/7 + logs + portfolio_state
- Import：粘贴 bundle → 恢复状态（带 schemaVersion 校验与错误提示）
- Confirm：对 Step4 或 Step5 的 orders 进行二次确认，写入 confirm_log
- Executed（回写）：用户手动下单后，写入 execution_log，并自动更新 portfolio_state（默认按确认单 100% 成交；允许手动覆盖）
- 复盘视图：支持查看历史 N 次 runs（输入/输出/AI 分析/确认/执行），并导出 JSON

## 7. UI / 路由与信息架构（IA）
- 主入口（建议）：`/daa/market/funds`（日常操作）
- 辅助入口：`/daa/dashboard`（全流程面板、导入导出、复盘）
- Deep-link：`/daa/step/1..7` 必须可访问且不割裂（能跳转回主入口并定位对应 step）

## 8. API / 集成要求（v0）
- 市场数据：
  - yfinance price-series：server-side 拉取，避免 CORS
  - OKX candles：server-side 拉取，避免 CORS
- Engine proxy：
  - `POST /api/daa/rebalance/simulate`（代理到后端引擎）
  - `POST /api/daa/rebalance/core`（纯本地 deterministic 核心逻辑）
- 任何敏感接口（余额/密钥）默认 localhost-only 或必须鉴权

## 9. 非功能性需求（NFR）
- 可用性：缺数据时给出明确缺口与下一步按钮（jump/cta），不让用户猜。
- 可靠性：同一输入尽量得到同一输出（尽量去随机性；如有随机必须显式记录种子/版本）。
- 性能：页面操作与本地计算应在可接受时间内完成（回测/扫描可给进度）。
- 安全：日志/错误响应不得泄露 token/密钥；公网路由最小暴露。

## 10. 验收标准（DoD）
### 10.1 最短闭环（必须通过）
- 从主入口完成一次 run：Step2（有事件）+ Step3（有 money_plan）+ Step6（有 profile）→ Step4 生成 recommendation →（可选 Step5）→ Confirm → Export bundle
- Export 的 bundle 可以 Import 回来，恢复各 step 状态，且 Import 不触发外部 API

### 10.2 回测与历史数据（必须通过）
- Step1 能在 yfinance/OKX 任一数据源跑出结果；且结果能被主入口摘要读取
- backtest drift rebalance（如提供）能产出稳定结果并可复制/复盘

### 10.3 AI 分析（v0 上线即必须满足）
- UI 明确标注“仅分析/不自动下单/需人工确认”
- 若输出 `ai_orders_draft`：必须通过与 Step4 一致的约束校验，并能一键“确认”写入 confirm_log
- 引用事件/推荐结果时可追溯（给出来源/链接或 event id）

### 10.4 复盘（必须通过）
- Dashboard 能查看历史 runs（至少包含：Step1 回测摘要、Step4 输出、Step5 分析文本、确认记录、执行回写记录、当时的 portfolio_state），并能展示每次执行前后仓位/现金变化

## 11. 开放问题（需要你确认/补充）
- v0 的“标的范围”：美股 ETF/港股 ETF/加密/混合？（影响数据源与 symbol 规范）
- Step3 的 max in/out：按“金额”还是“比例”限制？是单次限制还是日内/周内累计？
- Step4 的“持仓本金比例”定义：用成本还是市值？若无成本信息，是否用市值近似？
- Execution 的 reference price 策略：v0 采用“确认按钮时刻的最新价”，并将该 price snapshot 持久化到 execution_log，确保可复盘。
- 人因模型对 Step4 的具体作用：是影响风险上限、还是影响信号权重、还是影响阈值？
