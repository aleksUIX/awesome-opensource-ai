# Awesome Open Source AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](CONTRIBUTING.md)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0--1.0-lightgrey.svg?style=flat-square)](LICENSE)

> A curated, continuously updated list of the best open source AI projects: frontier open-weight LLMs, AI agent frameworks, coding and browser agents, agent memory systems, RAG tooling, vector databases, local inference engines, fine-tuning libraries, and generative models.

Open source AI moves fast. This list tracks the projects that actually matter right now: the open-weight models competing with closed frontier labs (DeepSeek, Llama, Qwen, GLM, Gemma, Kimi), the agent frameworks people are shipping production systems with, and the memory, retrieval, and inference tooling underneath them. Star counts are live via shields.io and reflect GitHub at time of viewing.

## Contents

- [Frontier Open-Weight LLMs](#frontier-open-weight-llms)
- [AI Agent Frameworks](#ai-agent-frameworks)
- [Coding and Browser Agents](#coding-and-browser-agents)
- [Agent Memory](#agent-memory)
- [RAG Frameworks and Vector Databases](#rag-frameworks-and-vector-databases)
- [Inference and Local LLM Tools](#inference-and-local-llm-tools)
- [Fine-Tuning and Training](#fine-tuning-and-training)
- [Multimodal and Generative AI](#multimodal-and-generative-ai)
- [Honorable Mentions](#honorable-mentions)
- [Contributing](#contributing)
- [License](#license)

## Frontier Open-Weight LLMs

- **[DeepSeek-V3](https://github.com/deepseek-ai/DeepSeek-V3)** ![GitHub stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-V3?style=flat-square&label=%20): 671B-parameter MoE (37B active) reasoning and chat model from DeepSeek AI. The release that triggered the January 2025 open-weight market shock.
- **[DeepSeek-R1](https://github.com/deepseek-ai/DeepSeek-R1)** ![GitHub stars](https://img.shields.io/github/stars/deepseek-ai/DeepSeek-R1?style=flat-square&label=%20): Reasoning-focused sibling to V3, trained with large-scale reinforcement learning on chain-of-thought.
- **[Llama](https://github.com/meta-llama/llama)** ![GitHub stars](https://img.shields.io/github/stars/meta-llama/llama?style=flat-square&label=%20): Meta's open model family. Llama 4 (Scout and Maverick) is the current flagship, a natively multimodal MoE.
- **[Grok-1](https://github.com/xai-org/grok-1)** ![GitHub stars](https://img.shields.io/github/stars/xai-org/grok-1?style=flat-square&label=%20): xAI's original 314B MoE release under Apache 2.0.
- **[Qwen3](https://github.com/QwenLM/Qwen3)** ![GitHub stars](https://img.shields.io/github/stars/QwenLM/Qwen3?style=flat-square&label=%20): Alibaba's flagship open model line, Apache 2.0, now iterating through hybrid linear-attention and MoE variants (3.5/3.6).
- **[Kimi K2](https://github.com/MoonshotAI/Kimi-K2)** ![GitHub stars](https://img.shields.io/github/stars/MoonshotAI/Kimi-K2?style=flat-square&label=%20): Moonshot AI's 1T-parameter (32B active) MoE, built and tuned for agentic tool use.
- **[OLMo](https://github.com/allenai/OLMo)** ![GitHub stars](https://img.shields.io/github/stars/allenai/OLMo?style=flat-square&label=%20): Allen Institute's fully open model: weights, code, and training data all public. Currently on OLMo 3.
- **[GLM-5](https://github.com/zai-org/GLM-5)** ![GitHub stars](https://img.shields.io/github/stars/zai-org/GLM-5?style=flat-square&label=%20): Zhipu / Z.ai's coding- and agent-oriented MoE with a 1M-token context window, MIT licensed.
- **[Gemma](https://github.com/google-deepmind/gemma)** ![GitHub stars](https://img.shields.io/github/stars/google-deepmind/gemma?style=flat-square&label=%20): Google DeepMind's open-weight family under Apache 2.0. Gemma 4 adds multimodal input and a 256K context window.

## AI Agent Frameworks

- **[n8n](https://github.com/n8n-io/n8n)** ![GitHub stars](https://img.shields.io/github/stars/n8n-io/n8n?style=flat-square&label=%20): Fair-code workflow automation platform with native AI agent nodes.
- **[AutoGPT](https://github.com/Significant-Gravitas/AutoGPT)** ![GitHub stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=flat-square&label=%20): The project that popularized autonomous agents, now a low-code agent-building platform.
- **[Dify](https://github.com/langgenius/dify)** ![GitHub stars](https://img.shields.io/github/stars/langgenius/dify?style=flat-square&label=%20): Visual, production-ready platform for building and running agentic workflows.
- **[LangChain](https://github.com/langchain-ai/langchain)** ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat-square&label=%20): The foundational toolkit for building LLM applications and agents.
- **[CrewAI](https://github.com/crewAIInc/crewAI)** ![GitHub stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat-square&label=%20): Role-based multi-agent orchestration with no LangChain dependency.
- **[LangGraph](https://github.com/langchain-ai/langgraph)** ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat-square&label=%20): Graph-based, stateful orchestration for production-grade multi-agent systems.

## Coding and Browser Agents

- **[browser-use](https://github.com/browser-use/browser-use)** ![GitHub stars](https://img.shields.io/github/stars/browser-use/browser-use?style=flat-square&label=%20): The library that lets LLM agents drive a real web browser.
- **[OpenHands](https://github.com/OpenHands/OpenHands)** ![GitHub stars](https://img.shields.io/github/stars/OpenHands/OpenHands?style=flat-square&label=%20): Open-source autonomous coding-agent platform, formerly OpenDevin.
- **[smolagents](https://github.com/huggingface/smolagents)** ![GitHub stars](https://img.shields.io/github/stars/huggingface/smolagents?style=flat-square&label=%20): Hugging Face's minimalist library for agents that write and execute code instead of JSON tool calls.

## Agent Memory

- **[Mem0](https://github.com/mem0ai/mem0)** ![GitHub stars](https://img.shields.io/github/stars/mem0ai/mem0?style=flat-square&label=%20): Universal memory layer API for AI agents. Stores and retrieves user and session facts across LLM calls.
- **[Graphiti](https://github.com/getzep/graphiti)** ![GitHub stars](https://img.shields.io/github/stars/getzep/graphiti?style=flat-square&label=%20): Real-time knowledge-graph construction engine purpose-built for agent memory.
- **[cognee](https://github.com/topoteretes/cognee)** ![GitHub stars](https://img.shields.io/github/stars/topoteretes/cognee?style=flat-square&label=%20): Self-hosted knowledge-graph memory platform for persistent, cross-session agent memory.
- **[Letta](https://github.com/letta-ai/letta)** ![GitHub stars](https://img.shields.io/github/stars/letta-ai/letta?style=flat-square&label=%20): Platform for stateful agents with self-editing long-term memory. Formerly MemGPT.
- **[MemOS](https://github.com/MemTensor/MemOS)** ![GitHub stars](https://img.shields.io/github/stars/MemTensor/MemOS?style=flat-square&label=%20): Research-grade "memory operating system" for LLMs, with hybrid retrieval and skill reuse.
- **[Zep](https://github.com/getzep/zep)** ![GitHub stars](https://img.shields.io/github/stars/getzep/zep?style=flat-square&label=%20): Memory and context-engineering platform for agents, built on Graphiti.

## RAG Frameworks and Vector Databases

- **[LlamaIndex](https://github.com/run-llama/llama_index)** ![GitHub stars](https://img.shields.io/github/stars/run-llama/llama_index?style=flat-square&label=%20): The dominant data and retrieval framework for RAG-driven agents.
- **[Milvus](https://github.com/milvus-io/milvus)** ![GitHub stars](https://img.shields.io/github/stars/milvus-io/milvus?style=flat-square&label=%20): Cloud-native vector database built for large-scale approximate nearest neighbor search.
- **[Qdrant](https://github.com/qdrant/qdrant)** ![GitHub stars](https://img.shields.io/github/stars/qdrant/qdrant?style=flat-square&label=%20): Rust vector search engine, a common backend for RAG and memory stacks.
- **[Chroma](https://github.com/chroma-core/chroma)** ![GitHub stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat-square&label=%20): Embedding database purpose-built for LLM application retrieval.
- **[Haystack](https://github.com/deepset-ai/haystack)** ![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat-square&label=%20): Production-oriented RAG and agent pipeline framework from deepset.
- **[Weaviate](https://github.com/weaviate/weaviate)** ![GitHub stars](https://img.shields.io/github/stars/weaviate/weaviate?style=flat-square&label=%20): Open source vector database with built-in hybrid search.

## Inference and Local LLM Tools

- **[Ollama](https://github.com/ollama/ollama)** ![GitHub stars](https://img.shields.io/github/stars/ollama/ollama?style=flat-square&label=%20): Run and manage local LLMs through a simple CLI and API. The default on-ramp for local AI.
- **[llama.cpp](https://github.com/ggml-org/llama.cpp)** ![GitHub stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=flat-square&label=%20): C/C++ inference engine with GGUF quantization. Runs on nearly any hardware, powers Ollama and many others.
- **[vLLM](https://github.com/vllm-project/vllm)** ![GitHub stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat-square&label=%20): High-throughput, memory-efficient production serving engine built around PagedAttention.
- **[LocalAI](https://github.com/mudler/LocalAI)** ![GitHub stars](https://img.shields.io/github/stars/mudler/LocalAI?style=flat-square&label=%20): Self-hosted, OpenAI-API-compatible engine for LLMs, vision, voice, image, and video, no GPU required.
- **[SGLang](https://github.com/sgl-project/sglang)** ![GitHub stars](https://img.shields.io/github/stars/sgl-project/sglang?style=flat-square&label=%20): Fast-growing high-performance serving framework for LLMs and multimodal models.

## Fine-Tuning and Training

- **[Transformers](https://github.com/huggingface/transformers)** ![GitHub stars](https://img.shields.io/github/stars/huggingface/transformers?style=flat-square&label=%20): The model definition, inference, and training framework underpinning most open-weight models.
- **[Unsloth](https://github.com/unslothai/unsloth)** ![GitHub stars](https://img.shields.io/github/stars/unslothai/unsloth?style=flat-square&label=%20): Fast, memory-efficient LoRA and QLoRA fine-tuning for LLMs.
- **[DeepSpeed](https://github.com/deepspeedai/DeepSpeed)** ![GitHub stars](https://img.shields.io/github/stars/deepspeedai/DeepSpeed?style=flat-square&label=%20): Microsoft's distributed training and inference optimization library (ZeRO and friends).
- **[PEFT](https://github.com/huggingface/peft)** ![GitHub stars](https://img.shields.io/github/stars/huggingface/peft?style=flat-square&label=%20): State-of-the-art parameter-efficient fine-tuning library (LoRA, prefix tuning, and more).

## Multimodal and Generative AI

- **[Stable Diffusion WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)** ![GitHub stars](https://img.shields.io/github/stars/AUTOMATIC1111/stable-diffusion-webui?style=flat-square&label=%20): The original full-featured web UI for Stable Diffusion image generation.
- **[ComfyUI](https://github.com/Comfy-Org/ComfyUI)** ![GitHub stars](https://img.shields.io/github/stars/Comfy-Org/ComfyUI?style=flat-square&label=%20): Node-graph based, modular UI and engine for diffusion image, video, and audio generation.
- **[FLUX.1](https://github.com/black-forest-labs/flux)** ![GitHub stars](https://img.shields.io/github/stars/black-forest-labs/flux?style=flat-square&label=%20): Official inference repo for the FLUX.1 image-generation model family.

## Honorable Mentions

Smaller, more niche, or in-transition projects that still deserve a link.

- **[Microsoft AutoGen](https://github.com/microsoft/autogen)**: Multi-agent conversation framework, now in maintenance mode. Community fork continues as [AG2](https://github.com/ag2ai/ag2).
- **[MetaGPT](https://github.com/FoundationAgents/MetaGPT)**: Multi-agent framework that simulates a software company's roles (PM, architect, engineer).
- **[OpenAI Agents SDK](https://github.com/openai/openai-agents-python)**: OpenAI's official lightweight agent framework, successor to Swarm.
- **[Flowise](https://github.com/FlowiseAI/Flowise)**: Drag-and-drop UI for building LLM and agent flows.
- **[Camel-AI](https://github.com/camel-ai/camel)**: Framework for building and studying multi-agent systems.
- **[SWE-agent](https://github.com/SWE-agent/SWE-agent)**: Agent that autonomously resolves GitHub issues, from Princeton and Stanford.
- **[GPT4All](https://github.com/nomic-ai/gpt4all)**: Desktop app and ecosystem for running local LLMs on consumer hardware.
- **[MLX](https://github.com/ml-explore/mlx)**: Apple's array and machine learning framework, optimized for Apple Silicon.
- **[Axolotl](https://github.com/axolotl-ai-cloud/axolotl)**: Streamlined fine-tuning framework and config wrapper for many LLM architectures.
- **[pgvector](https://github.com/pgvector/pgvector)**: Vector similarity search extension for Postgres.
- **[LanceDB](https://github.com/lancedb/lancedb)**: Embedded vector database for multimodal AI.
- **[text-generation-webui](https://github.com/oobabooga/textgen)**: Local LLM chat UI with an OpenAI/Anthropic-compatible API.
- **[MiniMax-M2](https://github.com/MiniMax-AI/MiniMax-M2)**: Cheap, fast, agentic-coding-oriented MoE from MiniMax.
- **[TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM)**: NVIDIA's enterprise inference optimization library.
- **[Falcon-H1](https://github.com/tiiuae/Falcon-H1)**: TII's hybrid SSM and attention model family.
- **[Granite](https://github.com/ibm-granite/granite-4.0-language-models)**: IBM's enterprise-oriented open model family.

## Contributing

Contributions welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) first, then open a pull request. Keep entries to one line, in the format `- **[Name](link)**: Description.`, and make sure the project is genuinely open source (an open license, not just "open weights with a restrictive custom license").

## License

[CC0 1.0 Universal](LICENSE). To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this list.
