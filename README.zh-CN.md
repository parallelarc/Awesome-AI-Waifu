# Awesome AI Waifu

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

> 📅 **最后更新时间**: 2025-12-20  
> ⚠️ **时效性说明**: 本文档中的项目 Star 数、技术栈和功能描述基于 2025 年 12 月的数据，AI 领域发展迅速，建议访问项目仓库获取最新信息。

一个精心策划的 AI Waifu 相关资源列表，包括工具、框架、模型、应用和社区资源。

## 关于 AI Waifu

AI Waifu 是个体化的智能伴侣系统，不仅仅是一个"聊天机器人"，而是集成了对话理解、记忆体系、语音/视觉交互、行为模拟与角色人格的高维智能体。它能够理解你、记住你、具备角色人格与技能，并在环境中主动执行任务。

### 核心能力

#### 🗣️ 自然语言理解与情感交流

- **大语言模型（LLM）**：用于对话生成与语义理解
- **情绪识别**：文本/语音情绪分类，调整回复风格
- **角色人格设定**：通过 Prompt/Persona 影响语言风格与情绪表达

#### 🧠 长期记忆与个人知识图谱

- **向量数据库 + RAG**：存储语义记忆，结合检索增强生成上下文相关的回复
- **上下文管理器**：维护对话窗口，跟踪话题状态，动态构建提示词以整合历史与当前情境
- **事实档案**：构建个人与公共知识图谱（人物、事件、概念、关系），形成个性化的知识网络
- **记忆分层**：短期记忆、长期记忆，记忆优先级以及衰减机制

#### 🎭 多模态交互

- **语音交互**：语音识别（STT）实现语音输入理解，语音合成（TTS）生成自然语音输出，支持 Speech-to-Speech 端到端语音对话
- **视觉与图像理解**：计算机视觉模型识别图像内容、面部表情、手势动作，实现视觉感知与理解
- **原子动作与表情库**：预定义的原子动作系统，驱动 Avatar 的情绪表达

#### 🤖 Agent 能力与 Skills 库

- **Agent Framework**：实现主动行为决策与任务规划
- **原子技能库**：日程提醒、天气查询、智能设备控制、数据检索、API 调用
- **工具调用体系**：让 AI 像助手一样执行命令，而不只是回答问题

#### 🔐 数据隐私与个人主权

- **本地推理优先**：在用户设备上运行模型和记忆库
- **本地存储**：用户个性化数据本地加密保存
- **开源与自托管**：由个人与社区推动的生态系统，保障隐私和自由

## 框架和工具

### AI Waifu 专用框架

- [AIAvatarKit](https://github.com/uezo/aiavatarkit) ⭐ ~457 - 通用型语音对话 + Avatar 框架，支持 STT/TTS 与多模态输入输出
- [ChatdollKit](https://github.com/uezo/ChatdollKit) ⭐ ~1.1k - 将 3D 模型转换为可聊天的智能体 SDK，支持语音和面部动作联动

### 通用 AI 基础设施

- [LangChain](https://github.com/langchain-ai/langchain) ⭐ ~122k - 用于构建由大型语言模型（LLM）驱动的应用程序的开源工程框架，提供组件化和标准化接口、Agent 与工作流支持、数据感知与外部集成能力，可作为构建 AI Waifu 的技术基础，管理对话逻辑、长期记忆（RAG + Vector DB）和复杂行为代理
- [letta](https://github.com/letta-ai/letta) ⭐ ~20k - 先进的状态记忆 AI Agent 平台，可用于构建长期学习与记忆层
- [chatterbox](https://github.com/resemble-ai/chatterbox) ⭐ ~16.4k - 开源的高质量 TTS 引擎，为角色提供自然的语音生成功能

## 应用和平台

- [AIRI](https://github.com/moeru-ai/airi) ⭐ ~16.1k - 高星级、接近 Neuro-sama 的 AI Companion 平台，支持实时语音与游戏互动
- [AIwaifu](https://github.com/HRNPH/AIwaifu) ⭐ ~499 - 可微调、可定制的开源 AI Waifu 平台，提供基础对话与角色设定框架
- [Soul of Waifu](https://github.com/jofizcd/Soul-of-Waifu) ⭐ ~413 - Windows 桌面 AI 角色/陪伴应用：支持语音对话（STT/TTS）、Avatar（图片/Live2D/VRM 3D）、角色卡 v2（PNG）与 lorebooks / 多 persona；可接入多种云端 API，也支持在应用内下载并运行本地 GGUF（Llama.cpp）
- [z-waif](https://github.com/SugarcaneDefender/z-waif) ⭐ ~410 - 强调本地自托管的 Waifu 系统，集成 VTuber 角色与语音互动
- [WaifuOS](https://github.com/uezo/WaifuOS) ⭐ ~12 - 提供一站式的 Waifu 角色 + AI 系统套件，包含语音合成与数据库支持
- [yuna-ai](https://github.com/yukiarimo/yuna-ai) ⭐ ~210 - 以 "Yuna" 角色为主线的陪伴式 AI 项目
- [ai-waifu](https://github.com/JarikDem-Bot/ai-waifu) - 结合 VTuber 和语音助手功能的 AI Waifu 语音聊天项目
- [CliWaifuTamagotchi](https://github.com/RodzinaSzy/CliWaifuTamagotchi) - CLI 终端风格的 Waifu 互动项目（小品级/爱好者项目）
- [SillyTavern](https://github.com/SillyTavern/SillyTavern) ⭐ ~21.1k - 强大的对话前端，可加载角色、模型和插件，提供人物故事式的对话体验
- [Project N.E.K.O.（猫娘计划）](https://github.com/Project-N-E-K-O/N.E.K.O) - 以开源驱动、公益导向的 UGC 平台，目标是构建与现实世界紧密相连的 AI 原生元宇宙，让数字生命能够理解、连接并与人共同成长

## 社区和资源

- [Awesome AI VTubers](https://github.com/proj-airi/awesome-ai-vtubers) - AI VTuber 相关项目与资源的精选清单，包含模型、工具链、框架与社区资源等
- [awesome-waifutech](https://github.com/corollari/awesome-waifutech) - AI Waifu 技术相关的精选列表(过时)

## 贡献

欢迎贡献！请阅读 [CONTRIBUTING.md](CONTRIBUTING.zh-CN.md) 了解如何参与。

## 许可证

本项目采用 [CC0-1.0](LICENSE) 许可证。


