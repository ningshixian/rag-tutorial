## RAG学习课程

### All-in-RAG

项目地址：https://github.com/datawhalechina/all-in-rag

笔记地址：https://www.yuque.com/ningshixian/xa7g6q/xxw371i6tvkav33l?singleDoc# 



### Advanced RAG Techniques

RAG_Techniques 由 Nir Diamant 创建，展示各种先进的 RAG 技术。从基础实现到专业级解决方案，该项目涵盖了33种不同的技术，每一种都配有详细的实现指南和示例代码。

项目地址：[RAG_Techniques](https://github.com/NirDiamant/RAG_Techniques) 



### Agentic RAG for Dummies

传统RAG系统常受限于简单的语义相似性检索，难以处理复杂问题，且容易产生"幻觉"——即生成看似合理却不符合事实的内容。

这个项目使用 LangGraph 构建的模块化 Agentic RAG

项目地址：[agentic-rag-for-dummies](https://github.com/GiovanniPasq/agentic-rag-for-dummies)



## 实战项目

### <font style="color:rgb(31, 35, 40);">RAG Systems: arXiv Paper Curator</font>

> 项目地址：[https://github.com/jamwithai/arxiv-paper-curator](https://github.com/jamwithai/arxiv-paper-curator)
>

<font style="color:rgb(51, 51, 51);">构建</font>**<font style="color:rgb(51, 51, 51);background-color:#FBF5CB;">生产级 RAG 系统的完整实战课程</font>**<font style="color:rgb(51, 51, 51);">——从基础关键词搜索到本地 LLM 智能问答，真正掌握企业级检索增强生成架构</font>

+ <font style="color:rgb(51, 51, 51);">系统化进阶路径：6 周循序渐进，涵盖 </font>`<font style="color:rgb(51, 51, 51);">Docker+FastAPI+PostgreSQL+OpenSearch+Airflow</font>`<font style="color:rgb(51, 51, 51);">基础设施搭建 → 自动化arXiv论文抓取与解析 → 生产级BM25关键词检索 → 智能文档切片与语义+关键词混合检索 → 本地LLM集成实时流式问答 → 生产监控与缓存优化 </font>
+ <font style="color:rgb(51, 51, 51);">反直觉设计：强调“关键词搜索是根基”，先打牢BM25精确匹配基础，再引入向量语义，避免单靠向量检索带来的召回偏差和难以解释 </font>
+ <font style="color:rgb(51, 51, 51);">真实生产力：本地Ollama LLM实现隐私保护，流式响应秒开，Gradio UI极简交互，Langfuse实现端到端请求跟踪，Redis缓存带来150~400倍响应加速与显著成本节约 </font>
+ <font style="color:rgb(51, 51, 51);">工具链全面：集成Jina AI嵌入生成，Docling科学PDF解析，Apache Airflow自动化调度，OpenSearch强大混合搜索，支持Python 3.12+及Docker Compose一键部署 </font>
+ <font style="color:rgb(51, 51, 51);">学以致用：配套Jupyter笔记本和详尽博客，手把手教你构建真正可上线的科研助手，适合AI工程师、软件开发者、数据科学家深度掌握RAG工程核心技术 </font>
+ <font style="color:rgb(51, 51, 51);">生产级配置管理与监控：统一.env配置，兼顾开发与生产环境，实时性能与成本监控，支持异常优雅降级，确保系统稳定可靠 </font>
+ <font style="color:rgb(51, 51, 51);">开源免费：MIT许可，零费用本地搭建，灵活接入外部API，自由扩展，助力AI工程师构筑未来AI基础设施 </font>

<font style="color:rgb(51, 51, 51);">细节与代码示例全公开，完整架构设计与实操指导，打造你自己的AI论文智能助理。</font>

![](https://cdn.nlark.com/yuque/0/2025/png/8420697/1762155912500-9344571f-2006-440e-8101-eebf7f9085ff.png)



### [HKUDS/LightRAG](https://github.com/HKUDS/LightRAG) 🌟16.8k ✔

简单快速的 GraphRAG 检索增强生成。比微软的GraphRAG简洁很多的LightRAG

地址：https://github.com/HKUDS/LightRAG 

![img](https://cdn.nlark.com/yuque/0/2025/png/8420697/1749172681660-f112bf52-15e3-42b8-bf21-2b486ec39296.png)

### 

### Yuxi-Know ✅

面向真实业务的 RAG + 知识图谱智能体

- **智能体开发**：基于 LangGraph，支持子智能体、Skills、MCPs、Tools 与中间件机制
- **知识库（RAG）**：多格式文档上传，支持 Embedding / Rerank 配置及知识库评估
- **知识图谱**：基于 LightRAG 的图谱构建与可视化，支持属性图谱并参与智能体推理
- **平台与工程化**：Vue + FastAPI 架构，支持暗黑模式、Docker 与生产级部署

GitHub: [github.com/xerrors/Yuxi-Know](https://github.com/xerrors/Yuxi-Know )



### cook-graph-rag (Neo4j) ✅ 

教程：[https://datawhalechina.github.io/all-in-rag/#/chapter9/01_graph_rag_architecture](https://datawhalechina.github.io/all-in-rag/#/chapter9/01_graph_rag_architecture?id=第一节-图rag系统架构与环境配置)
项目地址：https://github.com/datawhalechina/all-in-rag/tree/main/code/C9

在前面cook-rag章节的基础上，接下来构建一个更先进的图RAG系统。通过引入Neo4j图数据库和智能查询路由机制，实现真正的知识图谱增强检索，解决传统RAG在复杂查询和关系推理方面的局限性。

![image.png](https://cdn.nlark.com/yuque/0/2025/png/8420697/1762258478914-7935770c-57ee-4b85-9b5f-52e16b38c919.png)