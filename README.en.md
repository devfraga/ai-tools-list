<!-- Language: 🇧🇷 [Português](README.md) · 🇺🇸 English -->

<div align="center">

# 🤖 AI Agents List

**A curated collection of AI agents, frameworks, and tools.**

Projects, services, and platforms from the AI agent ecosystem — organized by category.

🇧🇷 [Português](README.md) · 🇺🇸 **English**

<br>

[![Instagram](https://img.shields.io/badge/Instagram-%40sujeitoprogramador-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/sujeitoprogramador/)
[![YouTube](https://img.shields.io/badge/YouTube-Sujeito%20Programador-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCLc5Bq2yfs-S3Zse3ZFRMEQ)

</div>

## 📑 Contents

- [Coding Agents](#-coding-agents)
- [Agent Frameworks](#-agent-frameworks)
- [Browser and Desktop Agents](#-browser-and-desktop-agents)
- [Voice Agents](#-voice-agents)
- [Creative AI](#-creative-ai)
- [Automation and Workflows](#-automation-and-workflows)
- [Customer Support and CRM](#-customer-support-and-crm)
- [Data and Research](#-data-and-research)
- [Agent Memory](#-agent-memory)
- [Local and Self-Hosted AI](#-local-and-self-hosted-ai)
- [Personal Autonomous Agents (community)](#-personal-autonomous-agents-community)
- [Multi-Agent Platforms](#-multi-agent-platforms)
- [Tools and Integrations (MCP)](#-tools-and-integrations-mcp)
- [Protocols and Standards](#-protocols-and-standards)
- [Observability and Evaluation](#-observability-and-evaluation)
- [Open-Source Models for Agents](#-open-source-models-for-agents)
- [Security, Guardrails and Governance](#-security-guardrails-and-governance)

---

## 💻 Coding Agents

### IDE-integrated AI

| Tool | Description | Pricing |
|------|-------------|---------|
| [Cursor](https://cursor.com) | VS Code fork. Composer mode for multi-file edits. Multi-model support. | Free / Paid |
| [GitHub Copilot](https://github.com/features/copilot) | Agent mode in VS Code. Issue-to-PR with Copilot Workspace. Multi-model. | Paid |
| [Devin (Windsurf)](https://devin.ai/) | Agentic Cascade mode. Project memory. Parallel agents. | Free / Paid |
| [JetBrains AI](https://www.jetbrains.com/ai/) | Deep integration across all JetBrains IDEs. Context-aware completions. | Included with IDE |
| [Tabnine](https://www.tabnine.com/) | Privacy-first. On-premise option. Fine-tuned on your code. | Free / Paid |
| [Kiro](https://kiro.dev) | Spec-driven development: specs → tasks → implementation. | Beta |

### Terminal and CLI

| Tool | Description | Pricing |
|------|-------------|---------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | Anthropic's CLI agent. Strong reasoning. Agent Teams feature. | Subscription / API |
| [OpenAI Codex CLI](https://github.com/openai/codex) | OpenAI's terminal agent. Agents SDK. Multi-agent. | Subscription |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Google's open-source terminal agent. ReAct loop. MCP support. Apache 2.0. | Free (Google account) |
| [Aider](https://github.com/paul-gauthier/aider) | OSS pair programmer. Git-integrated. Any LLM. | Free + API |
| [Cline](https://github.com/cline/cline) | VS Code extension. Full terminal and browser access. | Free + API |
| [OpenCode](https://github.com/opencode-ai/opencode) | BYOK terminal agent. | Free + API |

### Code review and security

| Tool | Description | Pricing |
|------|-------------|---------|
| [Qodo](https://www.qodo.ai/) | AI code review. Context-aware PR validation. | Free / Enterprise |
| [CodeRabbit](https://coderabbit.ai/) | AI PR reviewer. Inline suggestions and security. | Free OSS / Paid |
| [Snyk Code](https://snyk.io/) | AI security scanner. Real-time vulnerability detection. | Free / Enterprise |
| [PR-Agent](https://github.com/Codium-ai/pr-agent) | OSS PR reviewer. Auto describe, review, and improve. | Free (OSS) |

### App builders (prompt → app)

| Tool | Description | Pricing |
|------|-------------|---------|
| [Bolt.new](https://bolt.new) | Prompt to a full-stack web app in the browser. | Free / Paid |
| [Lovable](https://lovable.dev) | Describe, build, and deploy from chat. | Free / Paid |
| [v0 (Vercel)](https://v0.dev) | Prompt to React/Tailwind components. | Free / Pro |
| [Replit Agent](https://replit.com) | Full-stack from a prompt. Auto deploy. | Free / Paid |
| [Dyad](https://github.com/dyad-sh/dyad) | OSS. Local-first. No-code app builder. | Free (OSS) |

---

## 🧱 Agent Frameworks

### General purpose

| Framework | Language | Description |
|-----------|----------|-------------|
| [AI SDK](https://github.com/langchain-ai/langchain) | JS/TS | AI SDK standardizes integrating AI models across supported providers. |
| [LangChain](https://github.com/langchain-ai/langchain) | Py/JS | The most adopted. Modular architecture, memory, and tools. |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Py/JS | Graph-based orchestration. Stateful directed graphs. |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Py/JS | Data-focused. Great for RAG agents. |
| [Haystack](https://github.com/deepset-ai/haystack) | Py | Pipeline-based. Search and retrieval. |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | C#/Py/Java | Enterprise, from Microsoft. Azure integration. |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | Py | Type-safe. Clean Pythonic API. Production-ready. |
| [DSPy](https://github.com/stanfordnlp/dspy) | Py | Stanford. Programming instead of prompting. Auto-optimization. |
| [Mastra](https://github.com/mastra-ai/mastra) | TS | TypeScript-first. Observational memory. Apache 2.0. |
| [Google ADK](https://github.com/google/adk-python) | Py | Google's Agent Development Kit. Gemini-native. Multi-agent orchestration. |

### Multi-agent orchestration

| Framework | Language | Description |
|-----------|----------|-------------|
| [AutoGen](https://github.com/microsoft/autogen) | Py | Microsoft's multi-agent conversations. |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Py | Role-based "crew" members with goals and tools. |
| [MetaGPT](https://github.com/geekan/MetaGPT) | Py | PM, architect, and engineer roles. Simulates a software company. |
| [Strands Agents](https://github.com/strands-agents/sdk-python) | Py | AWS-backed. Model-driven tool use. |
| [CAMEL](https://github.com/camel-ai/camel) | Py | Role-based simulation. Collaborative reasoning. |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Py | Pioneer. Now a platform with a visual builder. |
| [AgentScope](https://github.com/modelscope/agentscope) | Py | Alibaba's multi-agent framework. |

### Lightweight / minimalist

| Framework | Language | Description |
|-----------|----------|-------------|
| [Smolagents](https://github.com/huggingface/smolagents) | Py | Minimal agents from HuggingFace. ~1000 lines. |
| [Agno](https://github.com/agno-agi/agno) | Py | Lightweight and model-agnostic. |
| [Upsonic](https://github.com/upsonic/upsonic) | Py | MCP support. Minimal setup. |
| [Portia AI](https://github.com/portia-ai/portia-sdk-python) | Py | Reliable agents in production. |

---

## 🌐 Browser and Desktop Agents

### Developer infrastructure

| Tool | Description |
|------|-------------|
| [Browser Use](https://github.com/browser-use/browser-use) | OSS browser-agent library. |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Vision-driven navigation, no coded selectors. |
| [Agent S2 (Simular)](https://github.com/simular-ai/Agent-S) | OSS GUI automation framework. |
| [Browserbase](https://browserbase.com) | Cloud browser infra for agents. Headless at scale. |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | MCP server for Playwright + AI agents. |
| [Scrapling](https://github.com/d4vinci/Scrapling) | An adaptive Web Scraping framework that handles everything from a single request to a full-scale crawl! |

---

## 🎙 Voice Agents

### Platforms and APIs

| Platform | Description | Pricing |
|----------|-------------|---------|
| [ElevenLabs](https://elevenlabs.io) | Industry reference. Conversational AI with RAG, multimodal, and batch calling. | Free / Paid |
| [Vapi](https://vapi.ai) | Developer-focused. Low latency, model-agnostic. | Usage-based |
| [Bland AI](https://bland.ai) | Outbound call automation. CRM integration. | Usage-based |
| [Voiceflow](https://voiceflow.com) | No-code voice and chat builder. Drag-and-drop. | Free / Paid |
| [Retell AI](https://retellai.com) | Realistic voice agents. Multilingual. Telephony. | Usage-based |
| [Deepgram](https://deepgram.com) | STT and TTS APIs. Low latency. | Usage-based |
| [AssemblyAI](https://assemblyai.com) | STT with diarization, sentiment, and summarization. | Usage-based |

### Open-source voice

| Tool | Description |
|------|-------------|
| [LiveKit Agents](https://github.com/livekit/agents) | Real-time voice/video agents, OSS. |
| [Rasa](https://github.com/RasaHQ/rasa) | OSS conversational AI. Self-hosted. NLU training. |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | OSS voice and multimodal conversational AI. |
| [Vocode](https://github.com/vocodedev/vocode-python) | OSS LLM-based voice agents. |

---

## 🎨 Creative AI

### Image generation

| Tool | Description | Pricing |
|------|-------------|---------|
| [Fal.AI](https://fal.ai/) | Multi-model tool for image / video generation. | Paid |
| [Runware](https://runware.ai/) | Multi-model tool for image / video generation. | Paid |
| [Midjourney](https://midjourney.com) | High artistic quality. Distinctive aesthetics. Discord + web. | Paid |
| [DALL·E](https://openai.com/dall-e) | Strong prompt understanding. Good with text in image. | Subscription |
| [FLUX](https://blackforestlabs.ai) | Open-weight. Photorealism focus. | Free / API |
| [Stable Diffusion](https://stability.ai) | Open-source. ControlNet, LoRAs, and ComfyUI ecosystem. | Free (OSS) |
| [Adobe Firefly](https://firefly.adobe.com) | Trained on licensed data. Integrated into Photoshop. | Adobe CC |
| [Google Imagen](https://deepmind.google) | State-of-the-art photorealism. API via AI Studio. | API |
| [Ideogram](https://ideogram.ai) | Best for text inside images. Logos and posters. | Free / Paid |
| [Leonardo AI](https://leonardo.ai) | Multi-model. Real-time canvas. 3D game assets. | Free / Paid |

### Video generation

| Tool | Description | Pricing |
|------|-------------|---------|
| [Google Veo](https://deepmind.google) | Native audio + video. High resolution. | API |
| [Kling](https://klingai.com) | Cinematic realism. Character consistency. | Free / Paid |
| [Runway](https://runwayml.com) | Motion Brush, Director Mode. Strong at editing. | Paid |
| [Sora](https://sora.com) | From OpenAI. Narrative coherence and realistic physics. | Subscription |
| [Pika](https://pika.art) | Beginner-friendly. Fast renders. | Free / Paid |
| [Luma Dream Machine](https://lumalabs.ai) | High resolution. Physics simulation. 3D/cinematic. | Paid |
| [Wan](https://github.com/Wan-Video/Wan2.1) | Best free OSS video generation. Self-hostable. | Free (OSS) |
| [HunyuanVideo](https://github.com/Tencent/HunyuanVideo) | Tencent OSS. Runs on consumer GPUs. | Free (OSS) |
| [LTX Video](https://github.com/Lightricks/LTX-Video) | OSS. Licensed data. Clear commercial terms. | Free (OSS) |

### Music and audio

| Tool | Description | Pricing |
|------|-------------|---------|
| [Suno](https://suno.ai) | Text to music. Full tracks with vocals. | Free / Paid |
| [Udio](https://udio.com) | High-fidelity music generation. Fine control. | Free / Paid |
| [Stable Audio](https://stableaudio.com) | High quality. Commercial license. | Free / Paid |
| [Meta AudioCraft](https://github.com/facebookresearch/audiocraft) | OSS. MusicGen + AudioGen. | Free (OSS) |

### 3D and design

| Tool | Description | Pricing |
|------|-------------|---------|
| [Meshy](https://meshy.ai) | Text/image to 3D. Game assets and products. | Free / Paid |
| [Tripo AI](https://tripo3d.ai) | Fast 3D from text/images. Multiple formats. | Free / Paid |
| [Vizcom](https://vizcom.ai) | Real-time AI rendering for industrial designers. | Paid |

---

## ⚡ Automation and Workflows

### Automation

| Tool | Description | Pricing |
|------|-------------|---------|
| [n8n](https://github.com/n8n-io/n8n) | OSS workflow automation with AI agent nodes. Visual + code. | Free / Cloud |
| [Zapier AI](https://zapier.com/ai) | Thousands of apps. Natural-language workflows. | Paid |
| [Make](https://make.com) | Visual workflow platform with AI features. | Free / Paid |
| [Activepieces](https://github.com/activepieces/activepieces) | OSS Zapier alternative, with AI. | Free (OSS) |
| [Temporal](https://github.com/temporalio/temporal) | Durable execution for long-running agent workflows. | Free / Cloud |
| [Oh My Hermes](https://github.com/rlaope/oh-my-hermes) | Workflow plugin for Hermes Agent with reviewed project memory, task-specific model settings, and research, planning, and code-review skills. Requires Hermes Agent. | Free (OSS); model costs separate |

### No-code agent builders

| Tool | Description | Pricing |
|------|-------------|---------|
| [Dify](https://github.com/langgenius/dify) | OSS LLMOps. Visual agent builder. RAG. | Free / Cloud |
| [Flowise](https://github.com/FlowiseAI/Flowise) | OSS drag-and-drop LLM agent builder. | Free (OSS) |
| [Langflow](https://github.com/langflow-ai/langflow) | Visual multi-agent and RAG builder. | Free / Cloud |
| [Lindy](https://lindy.ai) | No-code agents. Many integrations. | Paid |
| [Relevance AI](https://relevanceai.com) | No-code agents for sales, support, and research. | Free / Paid |

---

## 💼 Customer Support and CRM

### Support agents

| Tool | Description | Pricing |
|------|-------------|---------|
| [Intercom Fin](https://intercom.com) | Resolves a large share of tickets. Learns from the help center. | Paid |
| [Zendesk AI](https://zendesk.com) | Ticket routing, sentiment detection, Answer Bot. | Paid |
| [Ada](https://ada.cx) | Autonomous resolution. Multichannel. | Enterprise |
| [Freshdesk Freddy AI](https://freshworks.com) | Auto-triage, routing, and predictive analytics. | Paid |

---

## 📊 Data and Research

### Deep research

| Tool | Description | Pricing |
|------|-------------|---------|
| [Claude Deep Research](https://claude.ai) | Multi-step investigation with citations. | Subscription |
| [ChatGPT Deep Research](https://chat.openai.com) | Extended reasoning, web browsing, and reports. | Subscription |
| [Gemini Deep Research](https://gemini.google.com) | Google Search and Knowledge Graph. | Subscription |
| [Perplexity](https://perplexity.ai) | AI search with deep research mode. Real-time citations. | Free / Paid |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | Comprehensive autonomous research, OSS. | Free (OSS) |
| [STORM](https://github.com/stanford-oval/storm) | Stanford. Writes Wikipedia-style articles from scratch. | Free (OSS) |

### Data analysis

| Tool | Description | Pricing |
|------|-------------|---------|
| [Julius AI](https://julius.ai) | Upload CSV/Excel and ask in natural language. | Free / Paid |
| [Hex](https://hex.tech) | Collaborative data platform. AI analysis. | Free / Paid |
| [PandasAI](https://github.com/Sinaptik-AI/pandas-ai) | Chat with your data. Natural language to Pandas/SQL. | Free (OSS) |
| [TaskWeaver](https://github.com/microsoft/TaskWeaver) | Microsoft. Code-first data-analysis agents. | Free (OSS) |

### RAG and knowledge bases

| Tool | Description |
|------|-------------|
| [RAGFlow](https://github.com/infiniflow/ragflow) | OSS RAG engine with agent capabilities. |
| [Chroma](https://github.com/chroma-core/chroma) | OSS embedding database. Fast to build RAG. |
| [Weaviate](https://github.com/weaviate/weaviate) | OSS vector DB. GraphQL. Multimodal search. |
| [Qdrant](https://github.com/qdrant/qdrant) | High-performance vector DB in Rust. |
| [Milvus](https://github.com/milvus-io/milvus) | Cloud-native vector DB. Billion-scale. |
| [Pinecone](https://pinecone.io) | Managed vector DB. Serverless. Low latency. |

---

## 🧠 Agent Memory

Long-term memory layers that let agents remember context, preferences, and history across sessions.

| Tool | Description |
|------|-------------|
| [Mem0](https://github.com/mem0ai/mem0) | Memory layer for agents. Long-term across sessions. Self-hosted or managed. |
| [Zep](https://github.com/getzep/zep) | Long-term memory with a temporal knowledge graph. Production-focused. |
| [Letta (MemGPT)](https://github.com/letta-ai/letta) | Stateful agents with persistent memory. Successor to MemGPT. |
| [Cognee](https://github.com/topoteretes/cognee) | Agent memory combining knowledge graphs and vectors (ECL). |

---

## 🏠 Local and Self-Hosted AI

### Local LLM runners

| Tool | Description |
|------|-------------|
| [Ollama](https://github.com/ollama/ollama) | Run LLMs locally. Simple CLI. |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | C/C++ inference. CPU, GPU, and Apple Silicon. |
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput serving. PagedAttention. Production. |
| [LM Studio](https://lmstudio.ai) | Desktop app for local LLMs. Friendly UI. |
| [Jan](https://github.com/janhq/jan) | OSS ChatGPT alternative. 100% offline. |
| [LocalAI](https://github.com/mudler/LocalAI) | Drop-in replacement for the OpenAI API. No GPU required. |
| [GPT4All](https://github.com/nomic-ai/gpt4all) | OSS local chat. Runs on consumer hardware. |
| [Llamafile](https://github.com/Mozilla-Ocho/llamafile) | LLMs as a single file. Zero setup. Mozilla. |

### Fast inference providers

| Tool | Description |
|------|-------------|
| [Groq Cloud](https://console.groq.com) | Ultra-fast LPU inference. Free tier. |
| [Cerebras Inference](https://inference.cerebras.ai) | Very fast LLM inference. Free tier. |
| [Fireworks AI](https://fireworks.ai) | Serverless inference. Fine-tuning and RAG. |
| [Together AI](https://together.ai) | Hundreds of open models. Fast inference API. |

### Self-hosted agents and UIs

| Tool | Description |
|------|-------------|
| [Open WebUI](https://github.com/open-webui/open-webui) | Self-hosted ChatGPT-style UI. Access control and extensions. |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Self-hosted multi-model chat. All major providers. |
| [LobeChat](https://github.com/lobehub/lobe-chat) | OSS ChatGPT/Gemini-style UI. Plugin system. Multimodal. |
| [Anything LLM](https://github.com/Mintplex-Labs/anything-llm) | All-in-one app. RAG and agents. Desktop + Docker. |
| [DB-GPT](https://github.com/eosphoros-ai/DB-GPT) | Data interaction with a local LLM. 100% private. |

---

## 🐙 Personal Autonomous Agents (community)

| Agent | Description | Pricing |
|-------|-------------|---------|
| [OpenClaw](https://github.com/openclaw/openclaw) | Open-source, self-hosted AI agent. Runs on your machine and connects to WhatsApp, Telegram, Discord, Signal, Slack, and dozens of integrations, without routing your data through a third-party API. One of the fastest-growing GitHub repos. MIT. | Free (OSS) |
| [Hermes Agent](https://github.com/NousResearch/hermes-agent) | Autonomous agent from Nous Research. Runs in the terminal, desktop app, messengers, and IDEs. Creates its own "skills" after complex tasks to reuse them later. Works with many LLM providers and local models. | Free (OSS) |
| [Grok Bot](https://x.ai/bot) | No-code multi-agent platform. Each bot with its own environment and memory, with automatic handoff between them. | Paid |
| [Zero Claw](https://github.com/zeroclaw-labs/zeroclaw) | Fast, compact, fully autonomous personal AI assistant infrastructure, compatible with any operating system. | Paid |

---

## 🤝 Multi-Agent Platforms

| Platform | Description | Pricing |
|----------|-------------|---------|
| [ChatGPT](https://chat.openai.com) | GPTs, Deep Research, Canvas, agent mode, and vision. | Free / Paid |
| [Claude](https://claude.ai) | Tool use, computer control, MCP, and code execution. | Free / Paid |
| [Gemini](https://gemini.google.com) | Deep Think, Gems, multimodal. Google ecosystem. | Free / Paid |
| [Grok](https://x.ai) | Real-time data from X. Image generation. | Subscription |
| [Meta AI](https://meta.ai) | Llama-based. WhatsApp/Messenger. | Free |
| [Microsoft Copilot](https://copilot.microsoft.com) | Office 365 integration. Enterprise. | Free / Paid |
| [Coze](https://coze.com) | ByteDance's agent builder. Visual workflow. Plugin marketplace. | Free / Paid |

---

## 🔌 Tools and Integrations (MCP)

How agents reach the world: connectors for apps, web search, scraping, and thousands of actions via tool-calling and MCP servers.

| Tool | Description |
|------|-------------|
| [Composio](https://github.com/ComposioHQ/composio) | Hundreds of ready-made integrations and actions for agents, with managed auth. |
| [Firecrawl](https://github.com/mendableai/firecrawl) | Turns websites into clean data (Markdown/JSON) ready for LLMs. |
| [Tavily](https://tavily.com) | Web search API designed for agents and RAG. |
| [Exa](https://exa.ai) | AI-focused semantic web search. |
| [Apify](https://apify.com) | Web scraping and automation platform, with actors and MCP integration. |

---

## 📡 Protocols and Standards

| Protocol | Description |
|----------|-------------|
| [MCP (Model Context Protocol)](https://github.com/modelcontextprotocol) | Anthropic's open standard. "USB-C for AI." Industry standard for agent tools. |
| [A2A (Agent-to-Agent)](https://github.com/google/A2A) | Google's protocol for agent-to-agent communication. |
| [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling) | OpenAI's native tool use. JSON schema. |
| [Tool Use (Anthropic)](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) | Claude's native tool use. Structured JSON. |
| [OpenAPI](https://github.com/OAI/OpenAPI-Specification) | Industry-standard API specification. Foundation for agent tools. |

---

## 🔍 Observability and Evaluation

### Tracing and monitoring

| Tool | Description |
|------|-------------|
| [Langfuse](https://github.com/langfuse/langfuse) | OSS LLM observability. Traces, evals, and prompts. |
| [LangSmith](https://smith.langchain.com) | LangChain's platform. Tracing, testing, and evaluation. |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | OSS AI observability. Traces, evals, and embeddings. |
| [Helicone](https://github.com/Helicone/helicone) | OSS LLM observability. One-line integration. |
| [Braintrust](https://braintrustdata.com) | Eval-driven development. Experiment tracking. |

### Benchmarks

| Benchmark | Description |
|-----------|-------------|
| [SWE-bench](https://github.com/princeton-nlp/SWE-bench) | Industry standard for coding agents. |
| [AgentBench](https://github.com/THUDM/AgentBench) | LLM agent benchmark across 8 environments. |
| [GAIA](https://huggingface.co/gaia-benchmark) | General AI assistant. Real-world tasks. |
| [WebArena](https://github.com/web-arena-x/webarena) | Web agent benchmark on real websites. |

---

## 🧠 Open-Source Models for Agents

| Model | Org | Highlights |
|-------|-----|------------|
| [Llama](https://github.com/meta-llama) | Meta | Long context. Strong tool use. Open-weight. |
| [Qwen](https://github.com/QwenLM/Qwen3) | Alibaba | Agentic focus. MCP-native. Multimodal. |
| [DeepSeek](https://github.com/deepseek-ai/DeepSeek-V3) | DeepSeek | Low cost. Strong reasoning. |
| [Gemma](https://github.com/google-deepmind/gemma) | Google | Efficient models for consumer/IoT. |
| [GLM](https://github.com/THUDM/GLM-4) | Zhipu | Low hallucination rate. Strong at code. |
| [Mistral](https://mistral.ai) | Mistral | Function calling, JSON mode. European. |
| [Command R+](https://cohere.com) | Cohere | Optimized for RAG and enterprise tool use. |

---

## 🛡 Security, Guardrails and Governance

### Guardrails

| Tool | Description |
|------|-------------|
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | Structure, type, and quality guarantees for LLM outputs. |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | NVIDIA. Programmable conversation guardrails. |
| [Lakera Guard](https://lakera.ai) | Real-time protection. Prompt injection, leakage, and toxicity. |

---

<div align="center">

If this list helped you, leave a ⭐ and share it!

<sub>[@sujeitoprogramador](https://www.instagram.com/sujeitoprogramador/)</sub>

</div>
