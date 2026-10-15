![从身边的问题，开始做 AI 产品](assets/cover.svg)

# 你好，我是丁泓力，叫我 Hongli 也可以

我本科读生物信息学，硕士在康奈尔大学读医疗信息学与人工智能。现在在浙江大学“一带一路”国际医学院做人事与国际交流相关工作，也参与用 AI 改善业务流程。此前在卡罗莱纳精神病研究所实习，参与过临床辅助产品 VedAI 的需求研究、原型验证和上线推进。

工作中，我常常花时间查政策、核对表格、整理材料。精神科实习则让我接触到另一类问题：医生面对复杂病例，需要反复补充信息、查找依据。这些经历给了我做 AI 产品的具体想法，也让我有机会和使用者、项目负责人及开发同事一起讨论需求。

我平时喜欢试新模型和 AI 产品，也会读技术文档、看开源项目。感兴趣的想法会用 Codex 做成原型，自己操作一遍，看看在哪一步顺手、哪一步还得返工。目前在寻找 **AI 产品经理**的机会，也关注 **FD 方向**，希望继续做需求沟通、产品设计和实际落地相关的工作。

[个人作品站](https://dominicspace.com/#home) · [UniHR 源码](https://github.com/DominicHongliDing/UniHR-AgentOS) · [Clinical 产品介绍](https://github.com/DominicHongliDing/Clinical-Agent) · [EVO 产品与源码](https://github.com/DominicHongliDing/Agent-EVO)

## 我在做的三个项目

### 01 / UniHR AgentOS · 人事任务工作台

从自己的行政与人事工作出发，我想试试能不能少做一些重复的材料整理。UniHR 支持用日常语言说明要求，查政策原文，再生成可以修改的 Word 或 Excel。经办人可以核对出处、调整内容，接着完成手头的工作。

这是我持续开发的个人 Demo。我负责需求、流程和验收设计，借助 AI 编程工具实现原型。AI 在其中理解任务、检索政策和安排步骤，文件工具负责生成实际文件。

[看产品与源码 →](https://github.com/DominicHongliDing/UniHR-AgentOS) · [看交互展示 →](https://dominicspace.com/#unihr)

### 02 / Clinical Agent · 精神科临床辅助工作台

参与 VedAI 实习时，我定期与项目负责人、精神科医生和前后端工程师沟通。低年资及非精神科医生处理复杂病例时，既要整理患者信息，也要查证医学依据；前期反馈中，多轮对话遗漏信息和回答过于确定是需要处理的问题。

实习结束后，我继续做了个人项目 Clinical Agent。它按患者保存已确认的信息，用检索增强生成（RAG）查找医学资料，并将引用和待核对事项随回答展示。医生可以继续补充、提问和复核，临床决定仍由医生作出。

[看产品设计 →](https://github.com/DominicHongliDing/Clinical-Agent) · [打开工作台 →](https://dominicspace.com/apps/clinical/index.html)

### 03 / Agent EVO · 评测与改进工作台

前两个项目做下去以后，我遇到了一个很实际的问题：改了提示词或模型，怎么知道效果有没有变好？几条看起来不错的回答还不够，需要把以前出过问题的场景重新测一遍。

EVO 为此保存测试问题、实际回答和评审依据，供产品、业务和开发同事一起核对问题、比较版本。AI 帮忙起草测试题、评审回答和整理报告，测试标准与判断结果由人确认。目前提供源码、本地运行说明和在线案例。

[看产品与源码 →](https://github.com/DominicHongliDing/Agent-EVO) · [看设计思路 →](docs/agent-evo.md) · [看公开评测案例 →](https://dominicspace.com/apps/evaluation/index.html?space=history&view=story)

## 最近在关注

我最近比较关心 Agent 怎样记住用户补充的信息、什么时候需要调用工具，以及出了问题该怎么查。Context Engineering、Harness 这些概念，也是在做项目时逐渐理解的：哪些信息该给模型，哪些步骤需要软件控制，哪些地方要留给人判断。

欢迎交流新产品的体验、Agent 的实际用法，或你在工作里遇到的类似问题。如果你正在招聘 AI 产品相关岗位，也欢迎通过 GitHub 或作品站了解我的项目。
