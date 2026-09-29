# 老谷拆财报 · laogu-caibao

以数据为刃，剖市场真相。

面向 A 股散户的财经科普与财报解读账号，聚焦半导体芯片、宏观政策与热门赛道，固定栏目「价值投资之财报解读」全网连载中。我们把账号的方法论沉淀成了 **21 个开源财经 skill + 2 个工具**：纯 Markdown、平台中立、MIT 协议，Claude Code / Codex / 豆包智能体 / Workbuddy / 扣子 Coze / Trae 都能用。

## 30 秒上手

```bash
# 任选一个 skill 安装（例：研报精读）
npx skills add laogu-caibao/laogu-research

# 或一次装齐 16 个财经数据工具（MCP Server，零 key、零配置）
uvx laogu-mcp
```

## English

**Laogu Caibao ("Old Gu Reads Earnings Reports")** is a Chinese finance media brand for retail A-share investors. We publish **21 open-source AI agent skills** covering the full research loop: daily market briefs and post-close recaps, macro calendar explainers, company fundamentals and periodic-report deep dives, earnings-preview interpretation, valuation percentiles, broker-report digests, money-flow and dragon-tiger list analysis, share-unlock impact grading, convertible-bond and fund screening, plus an MCP server (`uvx laogu-mcp`) exposing 16 zero-key data tools.

Every skill is platform-neutral Markdown (works with Claude Code, Codex, Doubao, Workbuddy, Coze, Trae and any environment that reads Markdown instructions), installs with one command (`npx skills add laogu-caibao/<name>`), and follows two hard rules: **every number must come from a verifiable public source, and nothing is investment advice.**

## Skill 目录

### 每日必看

- [laogu-morning](https://github.com/laogu-caibao/laogu-morning) —— 每日市场简报：隔夜外盘、昨日复盘、今日看点
- [laogu-close](https://github.com/laogu-caibao/laogu-close) —— 盘后复盘：指数成交、板块涨跌、涨停异动、明日展望
- [laogu-macro](https://github.com/laogu-caibao/laogu-macro) —— 宏观日历解读：议息会议、PMI、CPI 等事件的影响链条

### 公司研究

- [laogu-fundamentals](https://github.com/laogu-caibao/laogu-fundamentals) —— A 股上市公司基本面速查
- [laogu-report](https://github.com/laogu-caibao/laogu-report) —— 定期报告深拆：年报 / 半年报 / 季报逐项拆解
- [laogu-earnings](https://github.com/laogu-caibao/laogu-earnings) —— 业绩预告解读：利润区间、同比口径、超预期判断
- [laogu-risk](https://github.com/laogu-caibao/laogu-risk) —— 财务风险预警：红黄绿灯财务体检表
- [laogu-value](https://github.com/laogu-caibao/laogu-value) —— 估值锚：历史分位 + 同行对比，只描述不荐股
- [laogu-research](https://github.com/laogu-caibao/laogu-research) —— 研报精读：核心逻辑、评级目标价、券商分歧点
- [laogu-notes](https://github.com/laogu-caibao/laogu-notes) —— 调研纪要解读：机构调研 / 电话会核心问答提炼

### 公告与资金

- [laogu-announcements](https://github.com/laogu-caibao/laogu-announcements) —— 财报与公告盯梢：定期报告、预告、分红、定增、减持
- [laogu-moneyflow](https://github.com/laogu-caibao/laogu-moneyflow) —— 资金流向解读：北向、两融、龙虎榜、ETF 份额
- [laogu-lhb](https://github.com/laogu-caibao/laogu-lhb) —— 龙虎榜夜报：机构 / 游资 / 深沪股通席位解读
- [laogu-unlock](https://github.com/laogu-caibao/laogu-unlock) —— 解禁冲击评估：抛压定级 + 历史案例参照
- [laogu-ipo](https://github.com/laogu-caibao/laogu-ipo) —— 打新日历：申购与上市时间轴

### 研报与资讯

- [laogu-news](https://github.com/laogu-caibao/laogu-news) —— 财经资讯解读：事件摘要、影响链条、多空判断

### 选股与进阶

- [laogu-screener](https://github.com/laogu-caibao/laogu-screener) —— 多策略选股：给定条件从全市场筛 A股，支持自然语言选股
- [laogu-fund](https://github.com/laogu-caibao/laogu-fund) —— 基金诊断：基金体检 + 经理行为审计 + 定投测算
- [laogu-sentiment](https://github.com/laogu-caibao/laogu-sentiment) —— 情绪周期：市场测温，7 维指标判 5 阶段（测温不预测拐点）
- [laogu-cb](https://github.com/laogu-caibao/laogu-cb) —— 可转债追踪：条款解读、溢价率、强赎预警、到期收益测算
- [laogu-thesis](https://github.com/laogu-caibao/laogu-thesis) —— 观点追踪：投资观点建档留存，到期回检"当初说的还成立吗"

### 工具箱

- [laogu-mcp](https://github.com/laogu-caibao/laogu-mcp) —— MCP Server：16 个财经数据 tool 的程序化数据层（零 key、纯公开接口），`uvx laogu-mcp` 一键安装
- [laogu-skill-maker](https://github.com/laogu-caibao/laogu-skill-maker) —— Skill 创作工坊：从选题、市场调研、SKILL.md 写作、数据源实测到冒烟测试、打包发布的 7 步流水线

## 常见问题

**Q：这些 skill 免费吗？**
全部免费开源（MIT 协议）。skill 本体是纯 Markdown 流程文件，复制就能用。

**Q：数据从哪来？需要申请 API key 吗？**
全部走公开渠道：上市公司公告、交易所公开数据、公开网页。不需要申请任何 key。纪律只有一条：数字必须来自可核验来源，取不到就标「未核验」，绝不编造。

**Q：会推荐股票吗？**
不会。所有 skill 只做结构化信息整理与解读，不输出买卖建议。个人观点，仅供参考，不构成投资建议。

**Q：支持哪些 AI 平台？**
平台中立 Markdown，Claude Code、Codex、豆包智能体、Workbuddy、扣子 Coze、Trae 等支持 Markdown 指令的环境都可用。数据工具用 [laogu-mcp](https://github.com/laogu-caibao/laogu-mcp) 接入任意支持 MCP 的客户端。

**Q：想自己做出同款财经 skill？**
从 [laogu-skill-maker](https://github.com/laogu-caibao/laogu-skill-maker) 开始：21 个财经 skill 踩坑沉淀出的 7 步流水线。

## 在哪里关注

- 抖音 / 微信视频号 / 今日头条 / 快手：搜索「老谷拆财报」

### 扫码关注

| 微信视频号 | 抖音 |
|---|---|
| ![视频号二维码](docs/qrcode-shipinhao.jpg) | ![抖音二维码](docs/qrcode-douyin.png) |
| 扫一扫，关注视频号 | 抖音号：gubaobao22 |

> 作者声明：个人观点，仅供参考，不构成投资建议。
