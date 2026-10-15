![从身边的问题，开始做 AI 产品](assets/cover.svg)

# 你好，我是丁泓力

本科就读于西交利物浦大学，专业是生物信息学，后来在康奈尔大学完成了医疗信息学与人工智能硕士学业。目前在浙江大学“一带一路”国际医学院从事人事与国际交流工作，也参与用 AI 改进日常业务流程。此前曾在卡罗莱纳精神病研究所实习，参与临床辅助产品 VedAI 的需求研究、原型验证和上线工作。

这里的项目，大多从这些经历中来。人事工作里，查政策、核对表格、准备材料占去了不少时间；精神科实习中，我看到医生处理复杂病例时，需要反复整理患者信息、查阅医学资料。我想试着用 AI 帮上忙，也在和使用者、项目负责人及开发同事的交流中，逐渐把想法做成了可以使用的原型。

平时喜欢试新模型和 AI 产品，读技术文档，也逛开源社区。遇到感兴趣的想法，会用 Codex 做个原型，看看实际用起来怎么样。我把值得分享的资源整理在「AI 见闻录」里，也欢迎来交流你的发现。

目前正在寻找 **AI 产品经理**的机会，也关注 **FDE 方向**。希望接下来的工作能让我更深入地接触用户，参与产品从需求讨论到交付使用的过程。

[个人作品站](https://dominicspace.com/#home) · [UniHR 源码](https://github.com/DominicHongliDing/UniHR-AgentOS) · [Clinical 产品介绍](https://github.com/DominicHongliDing/Clinical-Agent) · [EVO 产品与源码](https://github.com/DominicHongliDing/Agent-EVO)

## 我在做的三个项目

### 01 / UniHR AgentOS · 人事任务工作台

查到政策后，往往还要整理成通知、表格或会议材料。UniHR 想帮高校人事和行政经办人员把这段工作接起来：用日常语言说明要求，由 AI 检索政策、安排处理步骤，再调用文件工具生成可以编辑的 Word 或 Excel。经办人可以核对出处、修改内容，继续完成手头的事。

这是我从日常工作出发做的个人 Demo。我负责整理需求、设计流程和检查标准，并借助 AI 编程工具实现原型。

[看产品与源码 →](https://github.com/DominicHongliDing/UniHR-AgentOS) · [看交互展示 →](https://dominicspace.com/#unihr)

### 02 / Clinical Agent · 精神科临床辅助工作台

在卡罗莱纳精神病研究所实习、参与 VedAI 时，我定期与项目负责人、精神科医生和前后端工程师沟通。前期反馈让我注意到，低年资及非精神科医生处理复杂病例时，需要持续补充患者信息、查阅资料，而 AI 有时会遗漏前文，或在依据不足时给出过于肯定的回答。

带着这些问题，我在实习后继续做了个人项目 Clinical Agent。它围绕同一位患者保存已确认的信息，通过检索增强生成（RAG）查找医学资料，让医生能接着补充情况、提出问题，并在回答旁查看引用和待核对的内容。最终的临床判断仍由医生作出。

[看产品设计 →](https://github.com/DominicHongliDing/Clinical-Agent) · [打开工作台 →](https://dominicspace.com/apps/clinical/index.html)

### 03 / Agent EVO · 评测与改进工作台

随着前两个项目不断修改，我越来越需要知道：换了提示词或模型，原来的问题究竟修好了没有？只看几条回答很难判断，于是我开始保存出过问题的场景，在修改后重新测试。

EVO 把这个过程做成了工作台。产品、业务和开发同事可以对照测试要求查看回答，讨论哪里需要改，再比较修改前后的表现。AI 帮忙起草测试题、辅助评审和整理报告，评什么、结果是否合理，仍由人来确认。目前已公开源码、本地运行说明和在线案例。

[看产品与源码 →](https://github.com/DominicHongliDing/Agent-EVO) · [看设计思路 →](docs/agent-evo.md) · [看公开评测案例 →](https://dominicspace.com/apps/evaluation/index.html?space=history&view=story)

## AI 见闻录 · 资源与阅读分享

这个公开资源库收录 AI 网站、X / YouTube 作者，以及值得读的文章和视频。除了原始链接，我也会写上推荐理由和适合的读者，每周整理一次。希望你来逛一圈，能找到几样用得上的东西。

[打开 AI 见闻录 →](https://github.com/DominicHongliDing/AI-Fieldnotes) · [看文章与视频 →](https://github.com/DominicHongliDing/AI-Fieldnotes/blob/main/guides/reading.md)

## 最近在关注

最近在继续了解 Context Engineering 和 Harness Engineering。做项目时，用户补充的信息该怎样保留、哪些步骤需要工具完成、出错后怎样查清原因，都需要仔细处理。我想通过这些具体问题，把相关方法理解得更扎实。

欢迎聊聊你试过的 AI 产品、做项目的经验，或工作中还没解决的问题。如果你正在招聘，也可以通过上面的项目和作品站进一步了解我的工作。
