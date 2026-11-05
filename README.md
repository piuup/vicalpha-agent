[![VicAlpha AI 投研工作台，公募抱团与美股 13F 机构持仓界面](images/desk-highlights.png)](https://vicalpha.com/)

## 为机构级投资研究而设计的 AI 原生投研系统

在 VicAlpha，你可以用自然语言分析公司与市场、开发并回测策略、构建专属投研台，也可以直接描述需要关注的信号。平台实时跟踪你设定的条件，在信号触发时提醒你。

多市场数据库与底层知识库共同构成 VicAlpha 的研究基础。数据库覆盖 A 股、港股和美股，以及 ETF、基金等投资品种，为跨市场分析、持仓研究和策略回测提供数据；知识库为 AI 分析提供研究背景，帮助研究者结合上下文解读数据。

例如，研究行业轮动时，可以先问「近期哪些行业的资金流入在加速？」，再要求把观察指标整理成投研台，开发并回测一套轮动策略，最后设置信号：「当行业满足这套策略的入选条件时提醒我。」

**使用 [VicAlpha](https://vicalpha.com/) 开启专业投研与交易工作流。**

## 产品能力结构

多市场数据库与知识库提供研究资料，Sandbox（沙箱）提供研究执行环境。上层工作空间将这些基础能力与投研 Skills、策略回测和持续跟踪工具结合。

```mermaid
flowchart TB
    user["用自然语言提出研究需求"] --> workspace["VicAlpha · AI 投研工作空间"]
    workspace --> research["研究与分析"]
    workspace --> strategy["策略开发"]
    workspace --> tracking["持续跟踪"]
    research --> desks["调用投研 Skills<br/>分析公司与市场 · 构建投研台"]
    strategy --> test["选股与择时规则<br/>策略回测 · 收益与风险评估"]
    tracking --> alerts["事件跟踪 · 定时任务<br/>实时信号提醒与复盘"]
    data[("多市场数据库<br/>A 股 · 港股 · 美股 · ETF · 基金")] -. 研究数据 .-> workspace
    kb[("知识库")] -. 研究背景 .-> workspace
    sandbox["Sandbox 沙箱"] -. 执行环境 .-> workspace
```

## 研究工作空间与广场

你可以用自然语言发起研究，再沿同一条会话追问依据。例如：「今天半导体板块的上涨，是少数权重股带动，还是多数成分股都在涨？」

如果想先看一份成品，可以从研究广场浏览市场复盘、产业链报告和策略成果。回到工作空间，可以把自己的研究问题、会话和成果放在一起。

[**开始你的第一项研究**](https://vicalpha.com/)

| 研究入口 | 适合做什么 |
| --- | --- |
| 研究广场 | 按成果类型浏览公开研究，找到值得继续追问的问题。 |
| 工作空间 | 从新会话提出假设，保留上下文，从已有成果回到来源会话。 |

<table><tr><td width="50%" valign="top"><a href="images/research-plaza.png"><img src="images/research-plaza.png" alt="研究广场 · 浏览成果" width="100%"></a><br><sub>研究广场 · 浏览成果</sub></td><td width="50%" valign="top"><a href="images/workspace.png"><img src="images/workspace.png" alt="工作空间 · 发起研究" width="100%"></a><br><sub>工作空间 · 发起研究</sub></td></tr></table>

## 投研 Skills

你可以用自然语言指定研究任务。例如：「用财报体检分析这家公司，核对上期管理层承诺，并列出本期需要追问的异常变化。」

也可以直接选用 Skills 库中的 15 个官方模板。选择模板后即可开始对话，再补充标的、报告期或研究假设。

[**选择一个 Skill 开始研究**](https://vicalpha.com/skills)

| 官方分类 | 模板数 | 适用任务 |
| --- | --- | --- |
| 个股分析 | 6 | 公司一页纸、财报体检、技术面分析及投资论点论证。 |
| 市场研究 | 4 | 盘后复盘、市场环境研判与次日主线筛选。 |
| 资金流向 | 3 | 分析资金流向，跟踪国家队及龙虎榜动向。 |
| 投研台 | 2 | 围绕需要长期观察的问题开展投研台研究。 |

[![官方 Skills · 模板与示例问题](images/skills-library.png)](images/skills-library.png)

## 投研台

你可以用自然语言构建自己的机构级投研台。描述你想研究的问题、需要对照的指标和希望跟踪的信号，例如「帮我搭建一个行业轮动投研台，把市场广度、行业资金流和择时信号放在一起」。

你也可以直接使用[研究广场](https://vicalpha.com/plaza)里的现成投研台。下表按研究用途整理了官网发现目录中的 19 个投研台（2026 年 11 月 5 日），点击名称即可进入，部分入口需要登录。

[**开始构建自己的第一个投研台**](https://vicalpha.com/tracker)

### 市场与策略

| 投研台 | 研究问题 | 台内导航与专题 |
| --- | --- | --- |
| [A 股行情综合屏](https://vicalpha.com/dashboard/trk_01M544AT6G7NJDN1DGTHD3TZWJ) | 市场涨跌由哪些板块带动？ | 行情、情绪、板块、资金、龙虎榜 |
| [情绪温度计](https://vicalpha.com/dashboard/trk_01M6GATFGCSW9T3W052JCYZP3D) | 市场情绪处于什么位置？ | 温度总览、维度分解、指标明细、信号事件、历史复盘 |
| [涨停板](https://vicalpha.com/dashboard/trk_01M652CD3DX0AXP42X0KFD3ZYT) | 连板高度和题材热度如何演变？ | 情绪总览、连板天梯、题材主线、个股明细、次日表现 |
| [XHN-A股择时系统](https://vicalpha.com/live/trk_01M0Z1BYTTESV4KJRNQFY17243) | 左侧、同步与右侧信号何时一致？ | 综合看板、左侧抄底、同步跟踪、右侧逃顶、使用方法、指标体系 |
| [逆向投资](https://vicalpha.com/dashboard/trk_01M67TX7K5KDJ9TM5ZESM0CR7V) | 哪些低温行业出现拐点信号？ | 逆向总览、市场温度、行业逆向、候选榜、陷阱排雷、拐点信号 |
| [A 股产业链图谱](https://vicalpha.com/dashboard/trk_01M1R26Z79TDB92XS5M3ZA7AMJ) | 同一条产业链的上下游有哪些环节？ | 选择产业链、上中下游图谱。页面提供环节与产品的下钻说明 |

<table><tr><td width="50%" valign="top"><a href="images/market-temperature.png"><img src="images/market-temperature.png" alt="情绪温度计 · 六维贡献" width="100%"></a><br><sub>情绪温度计 · 六维贡献</sub></td><td width="50%" valign="top"><a href="images/timing-desk.png"><img src="images/timing-desk.png" alt="三阶段择时 · 综合评分" width="100%"></a><br><sub>三阶段择时 · 综合评分</sub></td></tr></table>

### 资金与交易结构

| 投研台 | 研究问题 | 台内导航与专题 |
| --- | --- | --- |
| [A股资金流投研台](https://vicalpha.com/live/trk_01M0KE8SD5E4FC9TYVX82JSR05) | 如何从资金需求、供给与广度形成日度判断？ | 日度报告共 12 节：结论、增量、供给、方向、承接、主体、行为、广度、趋势、阶段、交易、口径 |
| [A 股资金流](https://vicalpha.com/dashboard/trk_01M5MH0K50GYYV6EMYT674E7KP) | 哪些渠道和板块的资金动向值得跟踪？ | 总览、主力动向、板块跟踪、个股热图、两融杠杆、跨境资金、ETF 资金、龙虎榜、产业资本 |
| [A 股融资融券](https://vicalpha.com/dashboard/trk_01M61AJ1TDEH04E6QTJ82DAVJQ) | 杠杆周期走到哪里？哪些标的风险较高？ | 总览、杠杆周期、行业两融、个股两融、风险监测、个股详情 |
| [全 A 筹码结构](https://vicalpha.com/dashboard/trk_01M68EM7X3XGD7ZSFKGWQ0YMHR) | 不同板块的持仓成本和获利比例有何差异？ | 筹码总览、行业筹码、筹码筛选、个股筹码 |
| [A 股交易拥挤度](https://vicalpha.com/dashboard/trk_01M5NRYV1THPTBNSA5QZTZXCQC) | 拥挤集中在哪些行业、风格和个股？ | 总览、市场拥挤、行业拥挤、行业详情、风格拥挤、个股拥挤、个股详情、机构持仓 |
| [股票供给](https://vicalpha.com/dashboard/trk_01M6K5FQ4ZM6J04MDHVCFX88Z8) | 如何跟踪发行、减持、回购与解禁压力？ | 官网已列出；打开后提示「该台暂未接入」 |
| [股票ETF资金流](https://vicalpha.com/dashboard/trk_01M6J2TE6YHG3N1M1PTQYYR80Q) | 如何观察 ETF 净申购与成分股被动需求？ | 官网已列出；打开后提示「该台暂未接入」 |

<table><tr><td width="50%" valign="top"><a href="images/market-monitor.png"><img src="images/market-monitor.png" alt="资金流 · 市场总览" width="100%"></a><br><sub>资金流 · 市场总览</sub></td><td width="50%" valign="top"><a href="images/flow-direction.png"><img src="images/flow-direction.png" alt="资金流 · 行业方向" width="100%"></a><br><sub>资金流 · 行业方向</sub></td></tr></table>

[查看更多资金流趋势与阶段](images/flow-breadth.png)

### 机构与持仓

| 投研台 | 研究问题 | 台内导航与专题 |
| --- | --- | --- |
| [公募抱团](https://vicalpha.com/dashboard/trk_01M61AH34C7CZVPRZABP2H6FNV) | 公募持仓集中在哪里？拥挤组的表现如何？ | 抱团总览、个股拥挤度、个股透视、基金与资金、行业与仓位、抱团指数 |
| [A 股公募持仓](https://vicalpha.com/dashboard/trk_01M6BNGVY94CDVMMTZFJX6VPV6) | 不同基金公司怎样配置行业和个股？ | 持仓总览、公募排行、持仓详情、个股持仓、行业动向、持仓热力、公司比较 |
| [美股 13F 机构持仓](https://vicalpha.com/dashboard/trk_01M1WKA7BJYSXWN5T2XN6EED58) | 哪些机构调整了持仓？行业分布如何变化？ | 13F 总览、机构排行、机构详情、个股持仓、行业动向、持仓动向、机构对比 |
| [国家队全景](https://vicalpha.com/dashboard/trk_01M6FBPM1THJ7KECTFKEQB8DMB) | 国家队通过哪些 ETF 和持股组合参与市场？ | 全景总览、ETF 托底、持股组合、持仓全景、调仓动向、主体详情、个股透视 |
| [A 股十大流通股东](https://vicalpha.com/dashboard/trk_01M55196PFQ2GNCF02D9YJMPMM) | 重要股东持有哪些标的？筹码是否更集中？ | 股东总览、主体排行、主体详情、个股股东、行业动向、筹码集中度、事件信号 |
| [机构调研](https://vicalpha.com/dashboard/trk_01M6MGXHV4JVMCNXJPVQ0K27FG) | 哪些公司受到机构调研关注？ | 官网已列出；打开后提示「该台暂未接入」 |

<table><tr><td width="50%" valign="top"><a href="images/fund-holdings.png"><img src="images/fund-holdings.png" alt="公募抱团 · 拥挤度与收益" width="100%"></a><br><sub>公募抱团 · 拥挤度与收益</sub></td><td width="50%" valign="top"><a href="images/us-holdings.png"><img src="images/us-holdings.png" alt="美股 13F · 机构持仓" width="100%"></a><br><sub>美股 13F · 机构持仓</sub></td></tr></table>

---

## AI 策略回测

你可以把交易想法写成可检验的规则。例如：「回测双均线择时策略，以沪深 300 为基准，比较不同参数下的收益和最大回撤。」

在工作空间选择「策略构建 → 策略回测」输入需求。也可以先读已有官方报告，看清策略采用的参数、适用行情和失效场景。

[**进入工作空间，开始策略回测**](https://vicalpha.com/)

| 回测环节 | 要说明或检查的内容 |
| --- | --- |
| 提出需求 | 标的或样本池、比较基准、买卖规则，以及希望比较的参数。 |
| 解读报告 | 把收益与最大回撤、夏普放在一起看，再检查交易规则和样本表现分布。 |

<table><tr><td width="50%" valign="top"><a href="images/ai-backtest.png"><img src="images/ai-backtest.png" alt="自然语言输入 · 双均线需求示例" width="100%"></a><br><sub>自然语言输入 · 双均线需求示例</sub></td><td width="50%" valign="top"><a href="images/strategy-report.png"><img src="images/strategy-report.png" alt="已有官方报告 · 赫尔均线趋势" width="100%"></a><br><sub>已有官方报告 · 赫尔均线趋势</sub></td></tr></table>

[![已有报告 · 样本表现分布](images/backtest.png)](images/backtest.png)

## 内置策略

你可以从现成策略出发，再用自己的问题检验规则。例如：「比较低 PB 和 Piotroski F-Score：两者怎样选股，回撤表现有什么差异？」

官方策略库分别提供选股和择时策略。打开报告可以查看规则、历史收益与回撤，也可以克隆策略继续研究。下表列出八个示例。

[**浏览官方策略库**](https://vicalpha.com/strategies)

| 类型 | 策略 | 规则 |
| --- | --- | --- |
| 选股 · 价值 | 低 PB | 按账面价值相对市值筛选股票。 |
| 选股 · 质量 | Piotroski F-Score | 用九项财务信号衡量公司质量。 |
| 选股 · 价值 | 聂夫总回报 | 结合低市盈率、适度增长和分红筛选公司。 |
| 选股 · 资金流 | 基金持仓增持 | 关注公募持仓占比连续两个报告期上升的公司。 |
| 择时 · 复合 | 赫尔均线趋势 | 观察赫尔均线相对前值的升降。 |
| 择时 · 趋势跟踪 | 指数均线金叉 | 以短期与长期指数移动平均线的交叉跟踪趋势。 |
| 择时 · 趋势跟踪 | 半趋势通道翻转 | 用高低价格的平滑通道识别多空转换。 |
| 择时 · 趋势跟踪 | SuperTrend 趋势线 | 观察价格穿越基于 ATR 的轨道时，趋势方向是否翻转。 |

<table><tr><td width="50%" valign="top"><a href="images/selection.png"><img src="images/selection.png" alt="官方策略 · 选股" width="100%"></a><br><sub>官方策略 · 选股</sub></td><td width="50%" valign="top"><a href="images/timing.png"><img src="images/timing.png" alt="官方策略 · 择时" width="100%"></a><br><sub>官方策略 · 择时</sub></td></tr></table>

## 自选行情

把正在研究的标的加入自选，沿同一交易日对齐价格、成交量和技术指标。需要进一步分析时，可以在工作空间追问：「这段上涨是否伴随成交量放大？」

自选页支持切换周期、复权方式和指标。看短期波动时可用日线，对照更长趋势时可切换周线或月线。

[**打开自选行情**](https://vicalpha.com/watchlist)

| 观察维度 | 可用工具 |
| --- | --- |
| 价格与趋势 | K 线、均线、布林带及复权切换。 |
| 量能与动量 | 成交量、MACD、KDJ 和 RSI 等指标。 |

[![自选行情 · 同期价格、成交量与 MACD](images/watchlist.png)](images/watchlist.png)

## 实时信号提醒

你可以用自然语言定义关注条件。例如：「当自选股满足我的择时策略入场条件时提醒我。」平台持续跟踪条件，在信号触发时提醒你。

在信号页，可以从信号流开始，再用类别、方向和强度缩小范围；想比较多只股票时，也可以切换列表或热力视图。

[**查看交易信号**](https://vicalpha.com/signal)

| 筛选维度 | 可选范围 |
| --- | --- |
| 信号来源 | 策略、技术、形态、量价、资金、事件。 |
| 阅读方式 | 按方向与强度筛选，按股票合并或逐条查看。 |

[![信号页 · 类别、方向与强度](images/signals.png)](images/signals.png)

## 定时研究任务

把重复研究写成一条带频率的指令。例如：「每个交易日收盘后，复盘 A 股市场广度、成交额和领涨行业。」

从任务页点「新建任务」描述需求。已有任务可以按类型、频率和执行状态查找，便于检查哪些研究仍在跟踪、哪些需要处理。

[**开始设置你的第一个定时任务**](https://vicalpha.com/jobs)

| 任务管理 | 可用选项 |
| --- | --- |
| 研究类型 | 报告、选股、回测与策略、简报等。 |
| 执行频率 | 单次、每天、每个交易日、每周、每月或自定义。 |
| 运行状态 | 启用、已暂停、异常、已停止。 |

<table><tr><td width="50%" valign="top"><a href="images/scheduled-prompt.png"><img src="images/scheduled-prompt.png" alt="新建任务 · 指令示例" width="100%"></a><br><sub>新建任务 · 指令示例</sub></td><td width="50%" valign="top"><a href="images/jobs.png"><img src="images/jobs.png" alt="任务列表 · 频率与状态" width="100%"></a><br><sub>任务列表 · 频率与状态</sub></td></tr></table>

[打开 VicAlpha，开始研究 ↗](https://vicalpha.com/)
