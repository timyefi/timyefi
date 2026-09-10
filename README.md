# timye

固定收益研究，同时把研究能力做成可执行的工程件。

我相信的事情很简单：通用模型给的是通用的答案，真正有用的判断长在每个人自己的数据和经验里。所以我大部分时间在做一件事——把研究里的方法、口径、数据源拆成可以复述、可以核对、可以重组的零件，让它们跑在自己的机器上。

写这些代码的起点不是工具崇拜，是研究本身的需要。一份年报的附注口径、一条利差的拆解逻辑、一套久期管理的规则，如果只停在脑子里，就无法被质疑，也无法被传承。把它们写成 skill，判断第一次变得可以核对。

## 在做的事

**研究能力的工程化封装。** 把一个研究员的日常工作拆成数据、逻辑、判断三层，每层都是独立的零件，可以替换、可以组合、可以迭代。目前已覆盖财务分析、信用利差、资金面、城投、可转债、基金久期、国债期货、区域信用等方向。

**让能力跑在本机。** 数据、口径、客户信息不出本机，是这套东西的底线。本地化不止是隐私选择，也是成本选择。

**写清楚为什么这么做。** 每个系统都配一本技术架构手册，说明分层、接口契约和集成方式，让后来的人能接手，而不是只能仰视。

## 一点写作

关于 AI 如何落到个人与组织的研究工作里，我在 [这里](https://github.com/timyefi/blog) 陆续写一些观察。第一篇是 [这不是答案](https://github.com/timyefi/blog/blob/main/posts/this-is-not-the-answer.md)——Skill 不是答案，AGI 也不是答案，答案在使用过程中产生。

## 仓库导航

### 方法论与实践

- [research-skills](https://github.com/timyefi/research-skills) — Skill 中间件架构：AI 时代研究能力的工程化封装，以固定收益研究为例
- [skill20-arch](https://github.com/timyefi/skill20-arch) — 从 Skill 1.0 到 Skill 2.0：模块化中间件的工作论文与技术架构手册
- [meta-local-memory-arch](https://github.com/timyefi/meta-local-memory-arch) — 跨设备记忆召回引擎的技术架构手册
- [meta-backtest-arch](https://github.com/timyefi/meta-backtest-arch) — 多资产回测母框架的技术架构手册
- [gfqh-meta-skill-arch](https://github.com/timyefi/gfqh-meta-skill-arch) — 国债期货技术分析母框架：24 个分析框架与数据源体系

### 研究成果的 skill 化

- [financialanalysis](https://github.com/timyefi/financialanalysis) — 附注优先的企业财务分析引擎：从财报下载、解析到多阶段分析
- [financial-analyzer-arch](https://github.com/timyefi/financial-analyzer-arch) — 财务分析引擎的技术架构文档与使用教程
- [credit-spread-db-arch](https://github.com/timyefi/credit-spread-db-arch) — 信用利差数据库的架构手册
- [liquidity-db-arch](https://github.com/timyefi/liquidity-db-arch) — 资金面数据库的架构手册
- [fund-duration-db-arch](https://github.com/timyefi/fund-duration-db-arch) — 基金久期数据库的架构手册
- [convertible-bond-db-arch](https://github.com/timyefi/convertible-bond-db-arch) — 可转债数据库的架构手册

### 通用工具

- [web-data-scraper](https://github.com/timyefi/web-data-scraper) — 通用网站数据采集：分析师的思路，程序员的技巧
- [research-site-forge](https://github.com/timyefi/research-site-forge) — 买方研究者的一键建站与部署方案
- [dsh-deploy-portable-manual](https://github.com/timyefi/dsh-deploy-portable-manual) — 跨平台本地 AI 工作台部署与安全访问的手册

## 边界

架构手册与文档开源，Skill 源码多数不开源。非商业用途免费，商业用途需另行授权。文章采用 CC BY-NC 4.0。

---

<sub>固定收益研究 · Skill 工程化 · 本机优先</sub>
