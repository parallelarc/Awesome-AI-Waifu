# Awesome AI Waifu

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)

> 📅 **Last Updated**: December 20, 2025  
> ⚠️ **Timeliness Notice**: Project star counts, tech stacks, and feature descriptions in this document are based on December 2025 data. The AI field evolves rapidly, so please visit the project repositories for the latest information.

[中文文档](README.zh-CN.md)

A curated list of AI Waifu related resources, including tools, frameworks, models, applications, and community resources.

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

## Frameworks and Tools

### AI Waifu Specific Frameworks

- [AIAvatarKit](https://github.com/uezo/aiavatarkit) ⭐ ~457 - Universal voice dialogue + Avatar framework, supporting STT/TTS and multimodal input/output
- [ChatdollKit](https://github.com/uezo/ChatdollKit) ⭐ ~1.1k - SDK to convert 3D models into conversational agents, supporting voice and facial motion coordination

### General AI Infrastructure

- [LangChain](https://github.com/langchain-ai/langchain) ⭐ ~122k - Open-source engineering framework for building applications powered by large language models (LLM), providing componentized and standardized interfaces, Agent and workflow support, data awareness and external integration capabilities. Can serve as the technical foundation for building AI Waifu, managing dialogue logic, long-term memory (RAG + Vector DB), and complex behavior agents
- [letta](https://github.com/letta-ai/letta) ⭐ ~20k - Advanced stateful memory AI Agent platform for building long-term learning and memory layers
- [chatterbox](https://github.com/resemble-ai/chatterbox) ⭐ ~16.4k - Open-source high-quality TTS engine providing natural voice generation for characters

## Applications and Platforms

- [AIRI](https://github.com/moeru-ai/airi) ⭐ ~16.1k - High-star AI Companion platform approaching Neuro-sama level, supporting real-time voice and game interaction
- [AIwaifu](https://github.com/HRNPH/AIwaifu) ⭐ ~499 - Fine-tunable, customizable open-source AI Waifu platform providing basic dialogue and character setting framework
- [Soul of Waifu](https://github.com/jofizcd/Soul-of-Waifu) ⭐ ~413 - Windows desktop AI character/companion app: supports voice dialogue (STT/TTS), Avatar (image/Live2D/VRM 3D), character card v2 (PNG) with lorebooks/multi-persona; connects to various cloud APIs and supports downloading and running local GGUF (Llama.cpp) within the app
- [z-waif](https://github.com/SugarcaneDefender/z-waif) ⭐ ~410 - Locally self-hosted Waifu system emphasizing VTuber character and voice interaction
- [WaifuOS](https://github.com/uezo/WaifuOS) ⭐ ~12 - One-stop Waifu character + AI system suite, including voice synthesis and database support
- [yuna-ai](https://github.com/yukiarimo/yuna-ai) ⭐ ~210 - Companion AI project centered around the "Yuna" character
- [ai-waifu](https://github.com/JarikDem-Bot/ai-waifu) - AI Waifu voice chat project combining VTuber and voice assistant features
- [CliWaifuTamagotchi](https://github.com/RodzinaSzy/CliWaifuTamagotchi) - CLI terminal-style Waifu interaction project (hobby/enthusiast project)
- [SillyTavern](https://github.com/SillyTavern/SillyTavern) ⭐ ~21.1k - Powerful dialogue frontend that can load characters, models, and plugins, providing a story-driven conversation experience

## Community and Resources

- [awesome-waifutech](https://github.com/corollari/awesome-waifutech) - Curated list of AI Waifu technology-related resources (outdated)

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) to learn how to participate.

## License

This project is licensed under [CC0-1.0](LICENSE).

