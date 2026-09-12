<a href="https://timyefi.github.io/"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/hero-wide.svg?v=b645ac01"><img src="https://timyefi.github.io/assets/hero-tall.svg?v=026e94a0" width="100%" alt="研究工程笔记 · 把研究能力做成能跑的工程件"></picture></a>

> <sub>研究工程 · AI 工作流 · 本机优先　|　文章在 [写作站](https://timyefi.github.io/)　|　随笔在 [blog](https://github.com/timyefi/blog)</sub>

把研究里那些只存在于经验中的东西，一件件拆成可以复述、可以核对、可以重组的零件，让它们跑在自己的机器上。

写这些代码的起点不是工具崇拜，是工作本身的需要。一套口径、一条判断逻辑、一组需要反复执行的动作，如果只停在脑子里，就无法被质疑，也无法被传承。把它们写下来，判断才第一次变得可以核对。

## 方法论与实践

先想清楚为什么这么做，再谈怎么实现。每个体系都配一本技术架构手册，说明分层、接口契约与集成方式，让后来的人能接手。

<a href="https://github.com/timyefi/research-skills"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-research-skills-wide.svg?v=1084b624"><img src="https://timyefi.github.io/assets/card-research-skills-tall.svg?v=7aa23943" width="100%" alt="research-skills · Skill 中间件架构：把研究能力拆成数据、逻辑、判断三层，每层都是可替换的零件。以研究工作中的真实需求为例。"></picture></a>

<a href="https://github.com/timyefi/skill20-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-skill20-arch-wide.svg?v=0eb50419"><img src="https://timyefi.github.io/assets/card-skill20-arch-tall.svg?v=d25a1bc5" width="100%" alt="skill20-arch · 从 Skill 1.0 到 Skill 2.0：模块化中间件的工作论文与技术架构手册，讲清一次能力封装的完整取舍。"></picture></a>

<a href="https://github.com/timyefi/meta-local-memory-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-meta-local-memory-arch-wide.svg?v=bce1f348"><img src="https://timyefi.github.io/assets/card-meta-local-memory-arch-tall.svg?v=bebd60c1" width="100%" alt="meta-local-memory-arch · 跨设备记忆召回引擎的架构手册：双库融合索引，按机器区分来源，绝不串机。"></picture></a>

<a href="https://github.com/timyefi/meta-backtest-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-meta-backtest-arch-wide.svg?v=f9bbd0c3"><img src="https://timyefi.github.io/assets/card-meta-backtest-arch-tall.svg?v=fa5c5b32" width="100%" alt="meta-backtest-arch · 多资产回测母框架：固收、指数、ETF、个股四类资产共用同一套数据层与判断层。"></picture></a>

<a href="https://github.com/timyefi/gfqh-meta-skill-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-gfqh-meta-skill-arch-wide.svg?v=a0be9f42"><img src="https://timyefi.github.io/assets/card-gfqh-meta-skill-arch-tall.svg?v=45739c8f" width="100%" alt="gfqh-meta-skill-arch · 国债期货技术分析母框架：24 个分析框架与数据源体系，含基差、IRR 与多因子择时。"></picture></a>

## 研究能力的封装

把日常研究拆开重装：从财报下载、附注解析，到利差、资金面、久期、转债与区域信用，每个方向都是一件可以独立运转的工程件。

<a href="https://github.com/timyefi/financialanalysis"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-financialanalysis-wide.svg?v=804de089"><img src="https://timyefi.github.io/assets/card-financialanalysis-tall.svg?v=872ef152" width="100%" alt="financialanalysis · 附注优先的企业财务分析引擎：从财报采集、MinerU 解析到多阶段分析，判断顺序被写死在流程里。"></picture></a>

<a href="https://github.com/timyefi/financial-analyzer-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-financial-analyzer-arch-wide.svg?v=74983736"><img src="https://timyefi.github.io/assets/card-financial-analyzer-arch-tall.svg?v=c40a4e48" width="100%" alt="financial-analyzer-arch · 财务分析引擎的技术架构文档与使用教程：14 个 Agent、5 个阶段，每一步都可回勾到原始附注。"></picture></a>

<a href="https://github.com/timyefi/credit-spread-db-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-credit-spread-db-arch-wide.svg?v=57fb01c6"><img src="https://timyefi.github.io/assets/card-credit-spread-db-arch-tall.svg?v=e9a584f5" width="100%" alt="credit-spread-db-arch · 信用利差数据库的架构手册：核心利差、曲线结构与供给策略三类视角，支撑周报与策略专题。"></picture></a>

<a href="https://github.com/timyefi/liquidity-db-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-liquidity-db-arch-wide.svg?v=0d919f16"><img src="https://timyefi.github.io/assets/card-liquidity-db-arch-tall.svg?v=7bf3ba11" width="100%" alt="liquidity-db-arch · 资金面数据库的架构手册：资金价格、数量、央行操作、存单与 IRS 预期，九个维度 36 个视角。"></picture></a>

<a href="https://github.com/timyefi/fund-duration-db-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-fund-duration-db-arch-wide.svg?v=016725de"><img src="https://timyefi.github.io/assets/card-fund-duration-db-arch-tall.svg?v=c110f1c1" width="100%" alt="fund-duration-db-arch · 基金久期数据库的架构手册：净值回归测算经单基金校准，长端误差控制在 0.6 年以内。"></picture></a>

<a href="https://github.com/timyefi/convertible-bond-db-arch"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-convertible-bond-db-arch-wide.svg?v=98c7c9e6"><img src="https://timyefi.github.io/assets/card-convertible-bond-db-arch-tall.svg?v=3fe34d7e" width="100%" alt="convertible-bond-db-arch · 可转债数据库的架构手册：行情、估值、条款、供需、持仓与信用六类视角的完整拼装方式。"></picture></a>

## 工具与建站

研究之外顺手做的一些通用件：采集、建站、把工作台搬到哪台机器都能跑。

<a href="https://github.com/timyefi/web-data-scraper"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-web-data-scraper-wide.svg?v=cb05355b"><img src="https://timyefi.github.io/assets/card-web-data-scraper-tall.svg?v=3eeccfb9" width="100%" alt="web-data-scraper · 通用网站数据采集：分析师的思路，程序员的技巧。API 优先、浏览器兜底，输出 Markdown 与 CSV。"></picture></a>

<a href="https://github.com/timyefi/research-site-forge"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-research-site-forge-wide.svg?v=d206dbc8"><img src="https://timyefi.github.io/assets/card-research-site-forge-tall.svg?v=73e8768b" width="100%" alt="research-site-forge · 买方研究者的一键建站与免费部署方案：本地内容直接上线，不碰服务器也能有个人站。"></picture></a>

<a href="https://github.com/timyefi/dsh-deploy-portable-manual"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-dsh-deploy-portable-manual-wide.svg?v=2e4fa4a5"><img src="https://timyefi.github.io/assets/card-dsh-deploy-portable-manual-tall.svg?v=67bdf05f" width="100%" alt="dsh-deploy-portable-manual · 跨平台本地 AI 工作台部署手册：后台常驻、安全访问与自动恢复，Windows、macOS、Linux 同一套做法。"></picture></a>

## 写作

关于 AI 如何落到个人与组织的研究工作里，陆续写一些观察。文字来自本机实践中的一次具体观察，尽量写得可以照着做。

<a href="https://github.com/timyefi/blog"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-blog-wide.svg?v=7d8327a6"><img src="https://timyefi.github.io/assets/card-blog-tall.svg?v=17adc843" width="100%" alt="timyefi / blog · 随笔与文章仓库：Skill 不是答案，AGI 也不是答案，答案在使用过程中产生。"></picture></a>

<a href="https://timyefi.github.io/"><picture><source media="(min-width: 660px)" srcset="https://timyefi.github.io/assets/card-site-wide.svg?v=74eed975"><img src="https://timyefi.github.io/assets/card-site-tall.svg?v=d7066a1f" width="100%" alt="写作站 · timyefi.github.io · 按栏目与时间归档的在线阅读版，每一篇都写得可以照着做。"></picture></a>

---

**边界与许可。** 架构手册与文档开源，Skill 源码多数不开源。非商业用途免费，商业用途需另行授权。文章采用 CC BY-NC 4.0。

数据、口径与客户信息不出本机，是这套东西的底线。本地化不止是隐私选择，也是成本选择。
