# Agent EVO · 评测与改进工作台

EVO 是面向产品、业务和研发团队的 Agent 评测工作台。可以导入已有问答，按约定要求检查回答、记录问题，再用同一组测试核对修改效果。

[产品与源码](https://github.com/DominicHongliDing/Agent-EVO) · [在线案例](https://dominicspace-agent-showcase.peterzhukejie2020.chatgpt.site/apps/evaluation/index.html?space=history&view=story) · [返回个人主页](../README.md)

## 阅读入口

- [核心案例：回答审核与修复验证](https://github.com/DominicHongliDing/Agent-EVO/blob/main/docs/cases/correction-review.md)：对照一条病例更正测试，核实评审意见、查看执行依据并确定复测要求。
- [产品设计](https://github.com/DominicHongliDing/Agent-EVO/blob/main/docs/product-design.md)：解释用户分工、能力选择、异常处理和试用计划。
- [本地运行指南](https://github.com/DominicHongliDing/Agent-EVO/blob/main/docs/local-setup.md)：提供安装、模型配置和接入说明。

已有回答可以直接导入；需要取得新回答时，再由开发者连接自己的 Agent。只有产品说明时，AI 可以先草拟测试题，由业务人员修改确认。浏览历史案例无需 API Key，AI 出题、评审和报告需要配置个人模型账户。

我在迭代 UniHR 和 Clinical Agent 时，需要保留原始问题、实际回答和预期，改完再检查。EVO 由这些需要开始，源码和在线案例现已公开；真实团队使用效果仍待后续试用验证。
