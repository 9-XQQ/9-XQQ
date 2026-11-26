
<div align="center">

<!-- Orange Cat Banner -->
<img
  src="assets/profile-cat-banner.png"
  width="680"
  alt="Orange cat resting on a blue-gray platform"
/>

<p>
  <strong>自动化背景 · AI 应用开发 · 大模型系统</strong>
</p>

<p>
  <img src="https://img.shields.io/badge/Background-Automation%20%2F%20BCI-64748b?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Python%20Backend-2563eb?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-AI%20Systems-0e7490?style=flat-square" />
</p>

</div>

---

## 👋 About Me

你好！我是一名自动化专业硕士研究生，目前主要关注 **AI Systems、Python Backend 和 LLM Inference**。

喜欢从实际项目出发理解技术，关注从 AI 应用开发到推理服务、系统架构与底层优化的完整过程。

- 🔨 **Building：** Python Backend · LLM Agent · RAG · Inference Gateway
- 📖 **Exploring：** PyTorch · CUDA · MLIR
- 🎯 **Interested in：** AI Infrastructure · Inference Optimization · Compiler Engineering

---

## 🛠️ Tech Stack

### Languages & Development

<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,git,github,linux,vscode&theme=dark" />
</p>

### Backend & Database

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,postgres&theme=dark" />
</p>

![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-Database_Migrations-64748b?style=flat-square)
![HTTPX](https://img.shields.io/badge/HTTPX-Async_HTTP-0e7490?style=flat-square)
![Pytest](https://img.shields.io/badge/Pytest-Testing-2563eb?style=flat-square&logo=pytest&logoColor=white)

### AI Applications & Engineering

`LLM Agent` · `Tool Calling` · `RAG` · `BM25` · `Vector Retrieval` · `RRF` · `Ollama`

### Hardware & Systems

`Verilog` · `Vivado / Quartus` · `ModelSim` · `Digital Design` · `Embedded Systems`

---

## 🚀 Featured Projects

### ⚡ MiniTokenFactory — LLM 推理网关与服务工程

面向大模型推理服务场景，构建轻量化的 LLM Inference Gateway，探索模型调用、异步请求处理、流式输出与服务性能分析。

**核心实现：**

- **Inference Gateway：** 基于 FastAPI 构建 OpenAI 兼容 API，统一聊天补全请求入口。
- **Provider & Router：** 设计模型路由与 Provider 抽象层，实现请求分发及后端模型接入。
- **Streaming & Concurrency：** 实现 SSE 流式响应，并引入并发控制与限流机制。
- **Engineering & Evaluation：** 使用 HTTPX、Pytest 构建自动化测试，持续探索本地 GPU 推理及性能测量。

**Tech Stack**

`Python` `FastAPI` `AsyncIO` `HTTPX` `SSE` `PyTorch` `Ollama`

📂 [查看项目仓库](https://github.com/9-XQQ/MiniTokenFactory)

> **In Development** · 持续完善本地模型接入、推理 Benchmark 与服务性能分析。

---

### 🗺️ GroupHang — 多人协同出行规划 Agent

面向多人出行中地点信息分散、协作决策复杂等问题，开发支持自然语言地点解析、候选地点管理与人工确认的协同规划应用。

**核心实现：**

- **Backend Architecture：** 基于 FastAPI、异步 SQLAlchemy 与 PostgreSQL 构建后端服务。
- **Agent Workflow：** 实现地点提取、地图核验、候选消歧、方案预览及人工确认等受控执行环节。
- **External Integration：** 接入高德地图 API，处理地点搜索、地理编码与地图分享链接解析。
- **Testing & Evaluation：** 构建自动化测试、Mock 测试与离线 LLM 评测体系，关注地点解析准确性与执行可靠性。

**Tech Stack**

`Python` `FastAPI` `PostgreSQL` `LLM Agent` `Amap API` `Testing`

📂 [查看项目仓库](https://github.com/9-XQQ/GroupHang)

---

### 🧠 Product Knowledge System（RPK）— AI 产品知识与文档生成系统

面向复杂产品研发资料的知识组织与文档生产需求，探索将多格式资料处理、Agent 任务编排与结构化文档生成结合起来。

**核心实现：**

- **Knowledge Processing：** 支持 PDF、DOCX、XLSX 等资料接入，进行知识提取、结构化组织与来源管理。
- **Agent Orchestration：** 通过任务规划、执行方交接、状态管理及结果回收，组织多阶段研究与文档生产流程。
- **Document Generation：** 面向产品研究报告、IPD 材料等场景，支持多阶段内容组织与文档生成。
- **Presentation Harness：** 采用 `NarrativePlan → SlideSpec → PPTX` 的分阶段设计，探索内容策划、页面规格、素材管理与演示文稿渲染。

**当前效果：**

已形成产品报告与 IPD PPT 的实际生成案例，部分文档检查与生成流程已开展验证；内容质量、页面设计及端到端稳定性仍在持续优化。

**Technical Focus**

`AI Agents` `Workflow Orchestration` `Knowledge Management` `Document Processing` `Presentation Harness`

*持续开发中 · 相关成果需完成脱敏及授权检查后公开*

---

### 📚 Paper Research Agent — 论文研究助手

围绕学术论文的证据检索与引用溯源，探索结合多种检索策略的 RAG 工作流，重点关注检索质量、来源追踪及回答可信度。

**主要技术方向：**

- **Hybrid Retrieval：** 结合 BM25 与向量检索，提高候选文献片段覆盖能力。
- **Retrieval Optimization：** 使用 RRF 融合与重排序改善检索结果。
- **Evidence Grounding：** 关注原文定位、引用校验与可追踪的回答生成。
- **Evaluation：** 探索检索质量与引用一致性的测试和评测方法。

**Tech Stack**

`Python` `RAG` `BM25` `Vector Search` `RRF` `Reranking`

*研究与开发项目 · 仓库暂未公开*

---

## 🔬 Currently Learning

目前正在从 AI 应用工程逐步深入到 **LLM Inference & Compiler Infrastructure**。

| Direction | Current Focus |
|:---|:---|
| **PyTorch / CUDA** | GPU Tensor 操作、内存与计算、性能测量 |
| **LLM Inference** | Attention、KV Cache、TTFT / TPOT、吞吐量与延迟 |
| **Inference Serving** | Streaming、Batching、Concurrency、Model Routing |
| **MLIR** | SSA、Dialect、Operation、Pass、Lowering |
| **vLLM / Triton** | 后续深入推理框架与 GPU Kernel 优化 |

> Learning by building and measuring — 通过实际代码、测试与 Benchmark 理解系统行为。

---

## 💡 Engineering Interests

**AI Systems** · **LLM Inference** · **Compiler Infrastructure** · **Software Engineering**

关注可靠的 AI 系统设计、推理性能分析、编译优化，以及软硬件协同工程实践。

---

<div align="center">

### Thanks for visiting! 🐈

*Build · Measure · Learn · Improve*

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1120,100:0E7490&height=90&section=footer"
/>

</div>
