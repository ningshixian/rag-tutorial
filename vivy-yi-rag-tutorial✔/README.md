[vivy-yi/rag-tutorial](https://github.com/vivy-yi/rag-tutorial)

> 🚀 **最全面的中文RAG技术教程** - 从基础概念到生产部署，系统化掌握检索增强生成（Retrieval-Augmented Generation）技术。涵盖LangChain、LlamaIndex、向量数据库、Agent、GraphRAG等前沿技术。

| **在线文档**                                            | **Jupyter Notebooks**                               | **实战案例**                                                 |
| ------------------------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------ |
| [GitHub Pages](https://vivy-yi.github.io/rag-tutorial/) | [在线运行](https://vivy-yi.github.io/rag-tutorial/) | [案例文档](https://vivy-yi.github.io/rag-tutorial/projects/) |



## ✨ 特性

- 📚 **系统化学习路径**: 4个模块，20章内容，从入门到精通
- 💻 **17个Jupyter Notebooks**: 交互式学习环境，即学即练
- 🎯 **6个完整实战案例**: 企业级代码实现（智能客服、文档问答、AI研究助手等）
- 📊 **89张技术图表**: 深入理解架构和原理
- ✅ **30+练习题**: 巩固学习成果，附带详细参考答案
- 🚀 **前沿技术覆盖**: HyDE、Self-RAG、CRAG、GraphRAG、Deep Research、检索压缩等
- 🛠️ **完整技术栈**: LangChain、LlamaIndex、OpenAI、ChromaDB、Pinecone、Streamlit、FastAPI等
- 🌏 **中文优化**: 专为中文学习者设计，案例贴合实际应用场景



## 📖 教程大纲

### 模块1：基础入门 (5章)

```bash
docs/01-基础入门/
├── 00-教程导航.md
├── 01-RAG技术概述.md           # RAG技术发展历程
├── 02-环境搭建与工具准备.md      # 开发环境配置
├── 03-基础RAG实现.md            # 第一个RAG系统
├── 04-RAG评估基础.md            # 评估指标和方法
└── 05-模块1总结与项目.md        # 综合项目
```

### 模块2：核心优化 (8章)

```bash
docs/02-核心优化/
├── 06-嵌入模型深入.md            # Transformer嵌入
├── 07-高级分块策略.md            # 智能文档分块
├── 08-查询增强技术.md            # HyDE等技术
├── 09-混合检索与重排序.md        # Vector + BM25
├── 10-高级RAG模式.md            # 迭代、自适应检索
├── 11-性能优化.md                # 系统性能优化
├── 12-综合项目优化.md            # Intel优化案例
└── 13-检索压缩优化.md ⭐         # 上下文压缩
```

### 模块3：高级架构 (4章)

```bash
docs/03-高级架构/
├── 13-Agentic-RAG基础.md        # ReAct Agent
├── 14-高级Agent模式.md ⭐        # Deep Research + 多Agent
├── 15-知识图谱RAG.md            # GraphRAG实现
└── 16-多模态RAG.md              # 图文检索
```

### 模块4：生产部署 (5章)

```bash
docs/04-生产部署/
├── 17-环境配置.md                # 生产环境
├── 18-Docker部署.md             # 容器化部署
├── 19-监控和日志.md              # 可观测性
├── 20-安全实践.md                # 安全最佳实践
└── 22-最佳实践.md                # 生产级建议
```



## 🎯 实战案例

### 案例1：智能客服RAG系统

- **在线文档**: [查看](https://vivy-yi.github.io/rag-tutorial/projects/case1-customer-service/)
- **源码路径**: `projects/case1-customer-service/`
- **特点**: 基础RAG应用、多轮对话、Streamlit界面

### 案例2：技术文档问答系统

- **在线文档**: [查看](https://vivy-yi.github.io/rag-tutorial/projects/case2-doc-qa/)
- **源码路径**: `projects/case2-doc-qa/`
- **特点**: Vector + BM25混合检索、CrossEncoder重排序

### 案例3：AI研究助手Agent

- **在线文档**: [查看](https://vivy-yi.github.io/rag-tutorial/projects/case3-research-agent/)
- **源码路径**: `projects/case3-research-agent/`
- **特点**: ReAct Agent模式、ArXiv论文搜索、自动生成报告

### 案例4：企业知识图谱问答

- **在线文档**: [查看](https://vivy-yi.github.io/rag-tutorial/projects/case4-knowledge-graph/)
- **源码路径**: `projects/case4-knowledge-graph/`
- **特点**: GraphRAG实现、多跳推理、路径可视化

### 案例5：多模态产品问答

- **在线文档**: [查看](https://vivy-yi.github.io/rag-tutorial/projects/case5-multimodal/)
- **源码路径**: `projects/case5-multimodal/`
- **特点**: 图文混合检索、CLIP/GPT-4V支持

### 案例6：企业级RAG平台

- **在线文档**: [查看](https://vivy-yi.github.io/rag-tutorial/projects/case6-enterprise-platform/)
- **源码路径**: `projects/case6-enterprise-platform/`



### 案例: arXiv Paper Curator

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

### 案例：[HKUDS/LightRAG](https://github.com/HKUDS/LightRAG) 🌟16.8k ✔

简单快速的 GraphRAG 检索增强生成。比微软的GraphRAG简洁很多的LightRAG

地址：https://github.com/HKUDS/LightRAG 

![img](https://cdn.nlark.com/yuque/0/2025/png/8420697/1749172681660-f112bf52-15e3-42b8-bf21-2b486ec39296.png)

### 案例：Yuxi-Know

面向真实业务的 RAG + 知识图谱智能体

- **智能体开发**：基于 LangGraph，支持子智能体、Skills、MCPs、Tools 与中间件机制
- **知识库（RAG）**：多格式文档上传，支持 Embedding / Rerank 配置及知识库评估
- **知识图谱**：基于 LightRAG 的图谱构建与可视化，支持属性图谱并参与智能体推理
- **平台与工程化**：Vue + FastAPI 架构，支持暗黑模式、Docker 与生产级部署

GitHub: [github.com/xerrors/Yuxi-Know](https://github.com/xerrors/Yuxi-Know )

### 案例：cook-graph-rag (Neo4j) 

教程：[https://datawhalechina.github.io/all-in-rag/#/chapter9/01_graph_rag_architecture](https://datawhalechina.github.io/all-in-rag/#/chapter9/01_graph_rag_architecture?id=第一节-图rag系统架构与环境配置)
项目地址：https://github.com/datawhalechina/all-in-rag/tree/main/code/C9

在前面cook-rag章节的基础上，接下来构建一个更先进的图RAG系统。通过引入Neo4j图数据库和智能查询路由机制，实现真正的知识图谱增强检索，解决传统RAG在复杂查询和关系推理方面的局限性。

![image.png](https://cdn.nlark.com/yuque/0/2025/png/8420697/1762258478914-7935770c-57ee-4b85-9b5f-52e16b38c919.png)



## 🛠️ 技术栈

### 核心框架

- **LangChain**: 强大的LLM应用开发框架，支持链式调用、Agent等
- **LlamaIndex**: 专注于数据索引和检索的RAG框架

### 大语言模型（LLM）

- **OpenAI**: GPT-4, GPT-3.5-turbo
- **Anthropic**: Claude 3.5 Sonnet, Claude 3 Opus
- **本地模型**: 支持通过Ollama使用Llama 3、Qwen等开源模型

### 向量数据库

- **ChromaDB**: 轻量级本地向量数据库
- **Pinecone**: 全托管向量数据库服务
- **MongoDB Atlas Vector Search**: MongoDB原生向量搜索
- **Weaviate**: 开源向量搜索引擎

### 嵌入模型

- **OpenAI Embeddings**: text-embedding-3-small, text-embedding-3-large
- **HuggingFace**: sentence-transformers系列（all-MiniLM-L6-v2, m3e-base等）
- **FlagEmbedding**: 中文优化嵌入模型（bge系列）

### RAG优化技术

- **混合检索**: Vector Search + BM25关键词检索
- **重排序**: CrossEncoder、Cohere Rerank
- **查询增强**: HyDE（假设文档嵌入）、Query Rewriting、Query Expansion
- **高级分块**: Semantic Chunking、Recursive Character Splitting
- **检索压缩**: Context Compression、LLMContextualCompression

### Agent架构

- **ReAct Agent**: 推理+行动模式
- **Self-RAG**: 自我反思RAG
- **CRAG**: 校正RAG
- **Agentic RAG**: Agent驱动的动态检索
- **Deep Research Agent**: 多轮深度推理Agent

### 知识图谱

- **GraphRAG**: 结合知识图谱的RAG
- **Neo4j**: 图数据库存储
- **NetworkX**: 图计算和分析

### Web框架

- **Streamlit**: 快速构建交互式界面
- **FastAPI**: 高性能异步API框架
- **Jupyter**: 交互式Notebook环境



## 🚀 快速开始

### 环境要求

- Python 3.9+
- pip 或 conda

### 安装

```
# 1. 克隆仓库
git clone https://github.com/vivy-yi/rag-tutorial.git
cd rag-tutorial

# 2. 创建虚拟环境
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. 安装依赖
pip install -r requirements.txt
```

### 学习教程

#### 选项1：在线浏览（推荐）

访问 [GitHub Pages](https://vivy-yi.github.io/rag-tutorial/) 在线阅读完整教程

- ✅ 无需安装
- ✅ 完美渲染的Markdown和Notebooks
- ✅ 全文搜索功能
- ✅ 支持所有设备

#### 选项2：本地阅读文档

```
# 查看教程文档
cd docs/01-基础入门
open 01-RAG技术概述.md
```

#### 选项3：本地运行Notebooks

```
# 启动Jupyter
jupyter notebook

# 浏览到对应模块的notebook目录
# 例如：notebooks/module1/
```

#### 选项4：运行实战案例

```
# 例如运行案例1
cd projects/case1-customer-service
pip install -r requirements.txt
python main.py
```



## 📚 学习路径

### 路径1：快速入门 (2-3周)

```
docs/01-基础入门 → projects/case1-customer-service → docs/04-生产部署
```

### 路径2：系统学习 (6-8周)

```
docs/01-基础入门 → docs/02-核心优化 → docs/03-高级架构 → projects/case1-2-3
```

### 路径3：专家级 (10-12周)

```
所有docs模块 → 所有projects → 深入优化 → docs/04-生产部署
```

