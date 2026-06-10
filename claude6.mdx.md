# Claude Fable 5 来了订阅还值不值? 一文看懂新模型能力与 Token 计费变化\!

Anthropic 发布最强模型 Claude Fable 5。本文解读其编程与长任务能力、订阅计划包含期限、Token 计费价格变化,帮你判断 Claude 订阅是否仍然划算。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=MjQ3Y2JmMzdiZmU2ODViZjE2MTE2MmFkMWU0MTQyMTZfOTYyZTNkZGFkY2I3NjE0YmMwMzZiYjExMjZhNjg5NzNfSUQ6NzY0OTc1NzU2ODA5MjQ1Nzk1NF8xNzgxMTAyOTc5OjE3ODExODkzNzlfVjM)

Anthropic 刚刚发布了 Claude Fable 5这是其新的 Mythos 级模型中首个面向公众开放的版本,定位高于 Claude Opus,也是目前一般可用的 Claude 模型中能力最强的一款。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=ZjhjNjYyYmRkYzlmYjQ0ZmYyZTcyOGNmZGViYmNlNDZfMTFmOWI5YjcyNWI0NTk2Y2ZhZjBhNTJjOTk5NDk2ODRfSUQ6NzY0OTc1NzU0NjAyNjY1MDg1N18xNzgxMTAyOTc5OjE3ODExODkzNzlfVjM)

## Claude Fable 5 是什么?和 Mythos 5 有什么区别\!

按照 Anthropic 的官方说明,Fable 5 和 Mythos 5 本质上是同一底层模型的两个版本。Fable 5 面向公众开放,附带更严格的安全分类器;Mythos 5 则只通过可信访问计划提供给少数网络安全防御机构、关键基础设施提供方和后续的生物医学研究者。

对普通用户而言,实际能接触到的就是 Fable 5。当请求涉及网络安全、生物化学等高风险方向时,系统会自动改由 Claude Opus 4\.8 响应并提示用户;官方早期数据显示,超过 95% 的会话不会触发这种切换——日常的写作、编程、分析、设计任务基本不受影响。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=Zjk0NTFlODVjMDdiMzgyZDRhMjMwZmRmYTA1ZmIzOTJfODk2NGNhNjdhZWQ4ZTExNmJkZjIxNjY1NzU4NmRmYmZfSUQ6NzY0OTc1NzU0MTY5MzYwNjg1NF8xNzgxMTAyOTc5OjE3ODExODkzNzlfVjM)

## 能力提升:任务越长越复杂,优势越明显

从官方介绍和早期实测来看,Fable 5 的提升集中在几个方向:

软件工程是最被强调的能力。官方案例中,Stripe 让 Fable 5 处理一个 5000 万行代码库的迁移任务——原本需要工程团队两个多月的工作量,模型在一天内完成。Cognition 的 FrontierCode 评测也显示,它在复杂生产级代码任务上表现领先。

长任务与持久工作能力是另一个亮点。沃顿商学院教授 Ethan Mollick 的早期实测中,Fable 5 先生成 19 页设计文档,随后连续工作 9 个半小时,独立完成了一款研究工具的开发。在等时线地图项目中,它能调用多个 Agent 并行收集航班、铁路和道路数据,边写代码边测试边修正。

视觉理解方面,官方称 Fable 5 能从复杂科学图表中提取精确数字,也能根据网页截图重建应用源码,甚至只靠游戏画面就完成了《宝可梦火红》通关,无需额外的地图或导航辅助。

![Image](https://internal-api-drive-stream.feishu.cn/space/api/box/stream/download/authcode/?code=OGUzZDVlNzkxMWMyMzA4MzY1MDY3OTQ4ZmEyY2Y2MWRfMzdkMjlmN2RkMDM5ZjMyMTg0OGM3OGM4N2E0MjU0MjhfSUQ6NzY0OTc1NzU0Mjc0NjY4ODQ3NV8xNzgxMTAyOTc5OjE3ODExODkzNzlfVjM)

当然,实测也暴露出局限:Fable 5 仍会出错和遗漏,需要人工检查;更重要的是,长任务的 Token 消耗非常高——这正好引出下一个所有人都关心的问题。

## 订阅计划怎么变?关键时间点是 6 月 22 日

这是本次发布中对普通用户影响最大的部分,值得单独说清楚:

6 月 22 日之前:Fable 5 包含在 Pro、Max、Team 和按席位计费的 Enterprise 订阅计划内,订阅用户可以直接使用,不额外收费。

6 月 23 日起:Fable 5 将从这些订阅计划中移出,继续使用需要消耗 usage credits,即按实际用量付费。

API 价格:Fable 5 与 Mythos 5 定价相同,均为每百万输入 Token 10 美元、每百万输出 Token 50 美元。官方表示这已低于此前 Mythos Preview 的一半,但对高强度长任务来说仍然不便宜——有 Pro 用户反馈,只是跑了几个任务就用完了额度。

## 需要强调的是,这个变化只针对 Fable 5 这一个模型。Opus、Sonnet、Haiku 等模型仍然按原有方式包含在订阅计划中,Claude 订阅本身的核心价值没有消失。Token 计费时代:对不同用户意味着什么

订阅制的好处是成本可预期:每月固定支出,用多用少都一样。Token 计费则把真实成本摆到了台面上——每一次调用、每一个长任务,都对应明确的消耗。

对轻度用户\(日常问答、写作辅助、偶尔写代码\):现有订阅计划内的 Opus 4\.8 和 Sonnet 已经足够强,大多数场景下并不需要为 Fable 5 额外付费。订阅仍然是性价比最高的选择。

对重度生产力用户\(长链编程任务、研究项目、Agent 工作流\):Fable 5 的能力提升是实打实的,但需要开始做成本核算——这个任务交给 Fable 5 省下的时间,是否值得它消耗的 credits?一个实用的策略是用 Sonnet/Opus 处理常规环节,只把最难啃的部分交给 Fable 5。

对开发者:可以通过 Claude API 调用 `claude-fable-5`,按 Token 计费从发布日起已经全面可用。建议先用小规模任务测算实际消耗,再决定是否在生产环境中采用。

## 常见问题

Q:现在订阅 Claude Pro 还能用 Fable 5 吗? A:可以。6 月 22 日之前,Fable 5 包含在 Pro 及以上订阅计划中;之后需要消耗 usage credits 才能继续使用,但订阅内的其他模型不受影响。

Q:Fable 5 和 Opus 4\.8 该怎么选? A:日常任务两者差距不大,Opus 4\.8 包含在订阅内更划算;复杂长任务\(大型代码重构、多步研究、长时间 Agent 运行\)Fable 5 优势明显,但要考虑 Token 成本。

Q:Fable 5 的 API 价格是多少? A:每百万输入 Token 10 美元,每百万输出 Token 50 美元,与 Mythos 5 相同。

Q:为什么有时用 Fable 5 会被切换到 Opus 4\.8? A:这是 Anthropic 的安全机制。当请求涉及网络安全、生物、化学等高风险方向时,系统会自动改由 Opus 4\.8 响应并告知用户。官方数据显示超过 95% 的日常会话不会触发。

## 写在最后

Fable 5 的发布与其说是一次模型升级,不如说是 AI 行业计费体系调整的信号。模型在变强,而获得顶级能力的方式正在从「包月」走向「按量」。对用户来说,理解订阅计划包含什么、什么场景值得额外付费,会成为接下来使用 AI 的一项基本功。

Claude Fable 5 来了订阅还值不值? 一文看懂新模型能力与 Token 计费变化\! \- CZGPT



