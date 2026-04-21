# Awesome Agent Protocol

> AI 智能体协议，围绕Agent技术的三个核心方向：Agent连接外部世界（MCP）、Agent之间协作（A2A）、Agent与人类交互（ACP）

## 目录

- [MCP (Model Context Protocol) - Agent连接外部世界](#mcp-model-context-protocol---agent连接外部世界)
  - [官方协议](#官方协议)
  - [SDK/库](#sdk库)
  - [工具](#工具)
  - [应用](#应用)
- [A2A (Agent-to-Agent) - Agent之间协作](#a2a-agent-to-agent---agent之间协作)
  - [协作协议](#协作协议)
  - [多Agent框架](#多agent框架)
  - [协调工具](#协调工具)
- [ACP (Agent Client Protocol) - Agent与人类交互](#acp-agent-client-protocol---agent-client-protocol)
  - [客户端协议](#客户端协议)
  - [桌面应用](#桌面应用)
  - [Web应用](#web应用)
  - [移动应用](#移动应用)
- [相关列表](#相关列表)

## MCP (Model Context Protocol) - Agent连接外部世界

MCP 是连接Agent与外部世界的标准协议，让Agent能够访问文件系统、数据库、API等资源。

### 官方协议

- [Model Context Protocol](https://modelcontextprotocol.io) - Anthropic 官方的 MCP 协议文档和规范
- [mcp](https://github.com/modelcontextprotocol/mcp) - MCP 官方实现和 SDK

### SDK/库

- [mcp-python](https://github.com/modelcontextprotocol/python-sdk) - Python SDK 用于创建 MCP 服务器
- [mcp-typescript](https://github.com/modelcontextprotocol/typescript-sdk) - TypeScript/JavaScript SDK
- [mcp-go](https://github.com/modelcontextprotocol/go-sdk) - Go SDK

### 工具

- [mcp-cli](https://github.com/modelcontextprotocol/cli) - MCP 命令行工具
- [mcp-inspector](https://github.com/modelcontextprotocol/inspector) - MCP 服务器检查工具

### 应用

- [Claude Desktop](https://claude.ai/download) - 支持 MCP 的 Claude 桌面客户端
- [openEuler Intelligence](https://github.com/openeuler-mirror/openEuler-Intelligence) - 支持 MCP 服务管理的智能大模型平台
- [Operit AI](https://github.com/operit-ai/operit) - 支持完整 MCP 使用的 Android AI 助手

## A2A (Agent-to-Agent) - Agent之间协作

Agent之间的通信协议、协作框架和协调工具。

### 协作协议

- [Agent Communication Protocol (ACP)](https://github.com/agent-communication-protocol/acp) - Agent间通信协议
- [Multi-Agent System Protocol (MASP)](https://github.com/multi-agent-system/masp) - 多Agent系统协议

### 多Agent框架

- [AutoGen](https://github.com/microsoft/autogen) - Microsoft 多Agent对话框架
- [LangGraph](https://github.com/langchain-ai/langgraph) - LangChain 的多Agent图框架
- [CrewAI](https://github.com/joaomdmoura/crewAI) - 协作式多Agent框架
- [MetaGPT](https://github.com/geekan/MetaGPT) - 软件公司多Agent系统
- [ChatDev](https://github.com/OpenBMB/ChatDev) - 虚拟软件开发公司
- [Agents](https://github.com/aiwaves-cn/agents) - An Open-source Framework for Autonomous Language Agents

### 协调工具

- [AgentOps](https://github.com/AgentOps-AI/agentops) - Agent 可观测性和调试工具
- [LangSmith](https://www.langchain.com/langsmith) - LangChain 的 Agent 调试平台
- [AgentBoard](https://github.com/agentboard/agentboard) - 多Agent系统监控面板

## ACP (Agent Client Protocol) - Agent Client Protocol

Agent与人类交互的客户端协议和应用。

### 客户端协议

- [OpenAI Assistants API](https://platform.openai.com/docs/assistants/overview) - OpenAI 助手 API
- [Anthropic Messages API](https://docs.anthropic.com/claude/reference/messages-post) - Anthropic 消息 API

### 桌面应用

- [IntelliBar](https://intellibar.app) - macOS 菜单栏 AI 助手
- [MacGPT](https://www.macgpt.com) - macOS 原生 AI 应用
- [Chatbox](https://chatboxai.app) - 跨平台 AI 聊天客户端
- [SwiftChat](https://github.com/swiftchat-ai/swiftchat) - React Native 构建的跨平台 AI 聊天应用

### Web应用

- [ChatGPT](https://chat.openai.com) - OpenAI ChatGPT 网页版
- [Claude](https://claude.ai) - Anthropic Claude 网页版
- [Chatbot UI](https://github.com/mckaywrigley/chatbot-ui) - 开源 AI 聊天界面
- [ChatGPT Next Web](https://github.com/Yidadaa/ChatGPT-Next-Web) - 跨平台 ChatGPT 客户端

### 移动应用

- [Petey](https://petey.app) - iOS 和 watchOS AI 应用
- [ChatGPT Android](https://github.com/skydoves/chatgpt-android) - ChatGPT 安卓客户端
- [ETOS LLM Studio](https://github.com/etos-ai/etos-llm-studio) - watchOS 和 iOS 旗舰 AI 客户端
- [xhai Browser](https://github.com/xhai-browser/xhai) - Android 桌面管理 & AI 浏览器，DeepSeek 为默认 AI 引擎


## 贡献

欢迎贡献！请查看 [贡献指南](CONTRIBUTING_CN.md) 了解如何参与。

## 许可证

[CC0-1.0](license)
