# Awesome AI Waifu

<p align="center">
  <a href="https://awesome.re"><img src="https://img.shields.io/badge/Awesome-list-blue?style=for-the-badge" alt="Awesome"></a>
  <a href="http://creativecommons.org/publicdomain/zero/1.0/"><img src="https://img.shields.io/badge/License-CC0%201.0-lightgrey?style=for-the-badge" alt="License: CC0-1.0"></a>
  <a href="README.zh-CN.md"><img src="https://img.shields.io/badge/README-中文-red?style=for-the-badge" alt="中文"></a>
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge" alt="PRs Welcome"></a>
</p>

A curated list of AI Waifu related resources, including tools, frameworks, models, applications, and community resources.

> 📅 **Last Updated**: May 5, 2026 · ⚠️ Star counts are updated as of May 2026. The AI field evolves rapidly — visit project repositories for the latest.

## Contents

- [About AI Waifu](#about-ai-waifu)
- [Frameworks and Tools](#frameworks-and-tools)
- [Applications and Platforms](#applications-and-platforms)
- [Community and Resources](#community-and-resources)
- [Contributing](#contributing)
- [License](#license)

---

## About AI Waifu

AI Waifu is a personalized intelligent companion system that goes beyond a simple "chatbot". It's a high-dimensional intelligent agent that integrates conversational understanding, memory systems, voice/visual interaction, behavior simulation, and character personality. It can understand you, remember you, possess character traits and skills, and proactively execute tasks in its environment.

### Core Capabilities

#### 🗣️ Natural Language Understanding & Emotional Communication

- **Large Language Models (LLM)**: For dialogue generation and semantic understanding
- **Emotion Recognition**: Text/voice emotion classification to adjust response style
- **Character Personality**: Influence language style and emotional expression through Prompt/Persona

#### 🧠 Long-term Memory & Personal Knowledge Graph

- **Vector Database + RAG**: Store semantic memory, combine retrieval-augmented generation for contextually relevant responses
- **Context Manager**: Maintain conversation windows, track topic states, dynamically construct prompts to integrate history with current context
- **Fact Archives**: Build personal and public knowledge graphs (people, events, concepts, relationships) to form a personalized knowledge network
- **Memory Hierarchy**: Short-term memory, long-term memory, memory priority, and decay mechanisms

#### 🎭 Multimodal Interaction

- **Voice Interaction**: Speech recognition (STT) for voice input understanding, text-to-speech (TTS) for natural voice output, supporting end-to-end Speech-to-Speech dialogue
- **Visual & Image Understanding**: Computer vision models to recognize image content, facial expressions, gestures, enabling visual perception and understanding
- **Atomic Actions & Expression Library**: Predefined atomic action system to drive Avatar emotional expressions

#### 🤖 Agent Capabilities & Skills Library

- **Agent Framework**: Implement proactive behavior decision-making and task planning
- **Atomic Skills Library**: Schedule reminders, weather queries, smart device control, data retrieval, API calls
- **Tool Invocation System**: Enable AI to execute commands like an assistant, not just answer questions

#### 🔐 Data Privacy & Personal Sovereignty

- **Local Inference Priority**: Run models and memory banks on user devices
- **Local Storage**: User personalization data stored locally with encryption
- **Open Source & Self-hosted**: An ecosystem driven by individuals and communities, ensuring privacy and freedom

---

## Frameworks and Tools

### AI Waifu Specific Frameworks

- [AIAvatarKit](https://github.com/uezo/aiavatarkit) ⭐ ~593 - Universal voice dialogue + Avatar framework, supporting STT/TTS and multimodal input/output
- [ChatdollKit](https://github.com/uezo/ChatdollKit) ⭐ ~1.1k - SDK to convert 3D models into conversational agents, supporting voice and facial motion coordination

### General AI Infrastructure

- [LangChain](https://github.com/langchain-ai/langchain) ⭐ ~136k - Open-source engineering framework for building applications powered by large language models (LLM), providing componentized and standardized interfaces, Agent and workflow support, data awareness and external integration capabilities. Can serve as the technical foundation for building AI Waifu, managing dialogue logic, long-term memory (RAG + Vector DB), and complex behavior agents
- [letta](https://github.com/letta-ai/letta) ⭐ ~22k - Advanced stateful memory AI Agent platform for building long-term learning and memory layers
- [chatterbox](https://github.com/resemble-ai/chatterbox) ⭐ ~25k - Open-source high-quality TTS engine providing natural voice generation for characters
- [OpenClaw](https://github.com/openclaw/openclaw) ⭐ ~369k - Local-first personal AI assistant framework supporting 50+ messaging platforms (WhatsApp, Telegram, Discord, etc.), with voice interaction, live canvas, and skill system. Can serve as the conversational and agent backbone for AI Waifu systems
- [Hermes Agent](https://github.com/nousresearch/hermes-agent) ⭐ ~134k - Self-improving AI agent by Nous Research with built-in learning loop, cross-platform messaging (Telegram, Discord, Slack, etc.), multiple personalities (including "kawaii" mode), and autonomous skill creation

---

## Applications and Platforms

- [AIRI](https://github.com/moeru-ai/airi) ⭐ ~39k - High-star AI Companion platform approaching Neuro-sama level, supporting real-time voice and game interaction
- [AIwaifu](https://github.com/HRNPH/AIwaifu) ⭐ ~507 - Fine-tunable, customizable open-source AI Waifu platform providing basic dialogue and character setting framework
- [Soul of Waifu](https://github.com/jofizcd/Soul-of-Waifu) ⭐ ~668 - Windows desktop AI character/companion app: supports voice dialogue (STT/TTS), Avatar (image/Live2D/VRM 3D), character card v2 (PNG) with lorebooks/multi-persona; connects to various cloud APIs and supports downloading and running local GGUF (Llama.cpp) within the app
- [z-waif](https://github.com/SugarcaneDefender/z-waif) ⭐ ~518 - Locally self-hosted Waifu system emphasizing VTuber character and voice interaction
- [WaifuOS](https://github.com/uezo/WaifuOS) ⭐ ~24 - One-stop Waifu character + AI system suite, including voice synthesis and database support
- [yuna-ai](https://github.com/yukiarimo/yuna-ai) ⭐ ~210 - Companion AI project centered around the "Yuna" character (archived)
- [ai-waifu](https://github.com/JarikDem-Bot/ai-waifu) ⭐ ~134 - AI Waifu voice chat project combining VTuber and voice assistant features
- [CliWaifuTamagotchi](https://github.com/RodzinaSzy/CliWaifuTamagotchi) - CLI terminal-style Waifu interaction project (hobby/enthusiast project)
- [SillyTavern](https://github.com/SillyTavern/SillyTavern) ⭐ ~27k - Powerful dialogue frontend that can load characters, models, and plugins, providing a story-driven conversation experience
- [Project N.E.K.O.](https://github.com/Project-N-E-K-O/N.E.K.O) ⭐ ~1k - Open-source driven, public welfare-oriented UGC platform, aiming to build an AI-native metaverse closely connected to the real world, enabling digital life to understand, connect, and grow together with humans

---

## Community and Resources

- [Awesome AI VTubers](https://github.com/proj-airi/awesome-ai-vtubers) - Curated list of AI VTuber related projects and resources, including models, toolchains, frameworks, and community resources
- [awesome-waifutech](https://github.com/corollari/awesome-waifutech) - Curated list of AI Waifu technology-related resources (outdated)

---

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) to learn how to participate.

## License

This project is licensed under [CC0-1.0](LICENSE).

