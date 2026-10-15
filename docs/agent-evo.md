# Agent EVO · 评测与改进工作台

EVO 面向产品、业务与开发团队，用于准备测试要求、审核 Agent 回答、保存问题，并比较修复前后的结果。当前已公开源码、本地运行指南和在线案例。

[产品与源码](https://github.com/DominicHongliDing/Agent-EVO) · [在线案例](https://dominicspace-agent-showcase.peterzhukejie2020.chatgpt.site/apps/evaluation/index.html?space=history&view=story) · [返回个人主页](../README.md)

## 三种开始方式

| 已有材料 | 可以做什么 |
| --- | --- |
| 问答或多轮对话 | 导入回答，对照预期审核，保存有原文依据的问题 |
| 可调用的 Agent | 连接应用，用同一组题取得新结果并比较版本 |
| 产品说明 | AI 草拟测试题，人工修改并确认要求和题库版本 |

浏览历史案例无需 API Key；AI 出题、评审和报告需要配置个人模型账户。连接器支持应用留在原运行环境中，开发者配合配置接入。

## 设计重点

用户输入、预期、实际回答和引文一起查看。时间线先展示中文动作与结果，进入步骤看输入输出，再展开原始事件。人工审核可以修正模型判断并保留理由，材料不足的部分保持待确认。

已确认的问题保存为回归场景，修复后记录版本与评审条件，再判断是否达到要求。规则处理明确的格式字段，AI 辅助语义判断，业务人员确认标准和最终结论。

## 核心案例与后续阅读

[信息更正失败的审核与复测](https://github.com/DominicHongliDing/Agent-EVO/blob/main/docs/cases/correction-review.md)展示原始对话、审核依据、时间线分层与复测条件。用户将“两周”更正为“三天”后，Agent 再次返回通用补充信息提示，未完成总结；当前保留失败，修复后的同条件复测尚待补齐。

[完整产品设计](https://github.com/DominicHongliDing/Agent-EVO/blob/main/docs/product-design.md)说明范围、能力选择、异常与试用计划；[本地指南](https://github.com/DominicHongliDing/Agent-EVO/blob/main/docs/local-setup.md)提供安装和模型配置。

项目来自我迭代 UniHR 和 Clinical Agent 时核对修改效果的需要。我负责流程、审核界面和验收设计，并借助 AI 编程工具实现。下一步验证首次使用者能否独立完成审核与复测安排。
