# Multi-Agent & RAG System Examples

这是一个关于 **多智能体协作 (Multi-Agent)** 与 **RAG (检索增强生成)** 系统的实战示例合集。
本项目旨在通过具体的代码案例，演示如何构建现代化的 AI 应用。

## 📂 项目结构

本项目包含四个主要模块，适合不同阶段的学习者：

| 模块目录                                                       | 难度   | 类型         | 说明                                                                                                   |
| :------------------------------------------------------------- | :----- | :----------- | :----------------------------------------------------------------------------------------------------- |
| **[`example/vector_databases`](./example/vector_databases)**   | ⭐⭐⭐ | **RAG 实战** | **企业级知识库问答系统**。<br>基于 Milvus + LangChain + DashScope，包含完整的 Vue3 前端和 Flask 后端。 |
| **[`example/mcp_agent`](./example/mcp_agent)**                 | ⭐⭐⭐ | **MCP 协议** | **Model Context Protocol 智能体**。<br>演示最新的 MCP 协议标准，连接天气查询、文件读写等工具。         |
| **[`example/langgraph_example`](./example/langgraph_example)** | ⭐⭐   | 进阶教程     | **LangGraph 编排**。<br>从基础图结构到多智能体 Supervisor 模式的完整代码演练。                         |
| **[`example/langchain_example`](./example/langchain_example)** | ⭐     | 基础教程     | **LangChain 入门**。<br>Agent、Prompt 和 Tool 的基础用法示例。                                         |

## 🚀 快速开始

### 1. RAG 知识库系统 (`vector_databases`)

这是一个完整的前后端分离项目。

- **详细文档**: 请阅读 [PROJECT_DOCS.md](./example/vector_databases/PROJECT_DOCS.md)
- **后端**: `example/vector_databases` (Python/Flask)
- **前端**: `example/vector_databases/rag_front` (Vue3)

### 2. MCP 智能体 (`mcp_agent`)

演示了客户端-服务端架构的工具调用。

- **目录**: `example/mcp_agent`
- **运行**: `python api_server.py`

## ⚠️ 注意事项

- 运行代码前，请确保在各子目录下配置好 `.env` 文件（参考 `.env.example` 或代码中的说明）。
- 请勿将真实的 API Key 提交到版本控制系统中。

## 🛠️ 技术栈

- **Language**: Python 3.10+, Node.js
- **Frameworks**: LangChain, LangGraph, Flask, Vue3
- **Database**: Milvus (Vector DB)
- **LLM Provider**: Aliyun DashScope (Qwen/通义千问)
