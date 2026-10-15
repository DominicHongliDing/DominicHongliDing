![从身边的问题，开始做 AI 产品](assets/cover.svg)

# 你好，我是丁泓力 · Hongli

康奈尔大学医疗信息学与人工智能硕士，本科是生物信息学。目前在浙江大学“一带一路”国际医学院从事人事与国际交流事务，也参与 AI 赋能业务流程优化。此前在卡罗莱纳精神病研究所实习，参与了临床辅助产品 VedAI 的需求研究、原型验证和上线推进。

我的产品想法，大多来自工作里反复遇到的小麻烦：一份表格要核对几遍，换个问题又得重讲一遍病例，AI 给出了回答，却漏掉了用户刚刚补充的条件。我喜欢顺着这些问题往下问，也会用 Codex 把想法做成可以操作的原型，再回头检查它有没有帮上忙。

现在希望转向 **AI 产品经理**，也关注 **FD 方向**的机会。想做的工作很具体：走进业务现场，和使用者一起把问题讲清楚，再和团队把方案做出来、用起来。

[个人作品站](https://dominicspace.com/#home) · [UniHR 源码](https://github.com/DominicHongliDing/UniHR-AgentOS) · [Clinical 产品介绍](https://github.com/DominicHongliDing/Clinical-Agent) · [EVO 产品与源码](https://github.com/DominicHongliDing/Agent-EVO)

## 最近在做的产品

### 01 / UniHR AgentOS · 人事任务工作台

做行政和人事相关工作时，我发现不少时间花在查政策、对表格、改材料和衔接步骤上。UniHR 把这些任务放在同一张工作台：用自然语言说明要求，查到依据，生成可编辑的 Word / Excel，关键事项留给人确认。

这里的 AI 用来理解任务、查找政策、组织处理步骤；文件工具负责真正生成交付物。我关心的是经办人能不能核对、修改和接着用这些结果。

[看产品与源码 →](https://github.com/DominicHongliDing/UniHR-AgentOS) · [看交互展示 →](https://dominicspace.com/#unihr)

### 02 / Clinical Agent · 精神科临床辅助工作台

精神科机构实习时，我长期与项目负责人、医生和前后端工程师沟通。VedAI 的反馈让我注意到：面对复杂病例，年轻医生需要的是整理信息、查证依据和发现遗漏的帮助。实习结束后，我继续做了 Clinical Agent，把单轮问答延伸为围绕同一患者持续工作的工作台。

它复用已确认的病例信息，用 RAG 检索医学资料，将回答与来源放在一起。资料不足和需要医生确认的地方，也应该让人看见。

[看产品设计 →](https://github.com/DominicHongliDing/Clinical-Agent) · [打开工作台 →](https://dominicspace.com/apps/clinical/index.html)

### 03 / Agent EVO · 评测与改进工作台

做完前两个项目，我开始更在意另一个问题：这次修改究竟有没有用？一次顺利的演示回答不了它。EVO 因此从具体失败案例出发，把测试问题、实际回答、判断依据和版本对比放到一起，帮助产品人员决定先修什么、改完怎么验。

AI 在这里辅助准备测试问题、评审回答和整理报告，业务标准与最终判断由人确认。现在可以查看源码、在本地运行，也可以先从在线案例了解评测方法。

[看产品与源码 →](https://github.com/DominicHongliDing/Agent-EVO) · [看设计思路 →](docs/agent-evo.md) · [看公开评测案例 →](https://dominicspace.com/apps/evaluation/index.html?space=history&view=story)

## 我在持续学习什么

我会持续看新模型、试 AI 产品，也读技术文档和开源项目。最近尤其关心 Agent 如何保留上下文、什么时候调用工具，以及怎样判断结果是否可靠。遇到 RAG、Context Engineering 或 Harness 这类概念，我习惯把它放回自己的项目：它解决了哪个问题，增加了什么成本，又该怎样验证？

这些仓库记录的是我边学边做的过程。欢迎交流产品体验、具体场景，也欢迎指出设计里还没想周全的地方。
