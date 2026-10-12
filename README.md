## sanske1

AI Agent / RAG 应用开发 · 网络安全

把大模型能力接进实际工程——检索增强、多 Agent 协作、MCP 工具协议；
另一个方向是安全，把渗透测试的过程和结论沉淀成可检索的知识库。

### 项目

| 仓库 | 说明 |
|---|---|
| [boss-zhipin-autopilot](https://github.com/sanske1/boss-zhipin-autopilot) | BOSS直聘 半自动投递 Claude Code Skill：用 adb 驱动真机 App，脚本负责开 App、切页、读 JD、滚动、去重，人只在「读完 JD 再决定投不投」这一步介入 |
| [windows-rpa](https://github.com/sanske1/windows-rpa) | Windows 平台视觉 RPA 实践记录：以真实电子表格软件为对象的「视觉识别 → 自动操作」链路实测结论 |
| [mineral-daily-brief](https://github.com/sanske1/mineral-daily-brief) | 矿业日报 Agent：3 个 MCP server 分别供应矿产价格 / 新闻 / 研报，LangGraph 编排意图判断与工具调用，一句话生成 Markdown 日报 |
| [knowledge-agent](https://github.com/sanske1/knowledge-agent) | 基于大语言模型的企业级知识库 Agent：多格式文档 AI 加工入库 + Redis 向量检索 + LangGraph/MCP 智能体问答 |
| [RAG_injection](https://github.com/sanske1/RAG_injection) | 渗透测试 RAG 知识库：切块 + bge-m3 向量化 + Milvus 检索，通过 MCP 工具供 Claude Code 在渗透测试中检索取用 |
| [Multi-Agent-Injection](https://github.com/sanske1/Multi-Agent-Injection) | 基于 LangChain 的多 Agent 协作式自动化渗透测试系统，规划—执行—动态重规划的闭环（复现） |
| [android-rpa-crawler](https://github.com/sanske1/android-rpa-crawler) | 基于 Android 无障碍树的 RPA 列表数据采集框架 |

### 技术栈

Python · FastAPI · LangGraph · LangChain · MCP · RAG · Milvus · Redis · MySQL · Ollama · Docker
