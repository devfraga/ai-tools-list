<!-- Idioma: 🇧🇷 Português (padrão) · 🇺🇸 [English](README.en.md) -->

<div align="center">

# 🤖 Lista de Agentes de IA

**Uma coletânea curada de agentes de IA, frameworks e ferramentas.**

Projetos, serviços e plataformas do ecossistema de agentes de IA — organizados por categoria, em português.

🇧🇷 **Português** · 🇺🇸 [English](README.en.md)

<br>

[![Instagram](https://img.shields.io/badge/Instagram-%40sujeitoprogramador-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/sujeitoprogramador/)
[![YouTube](https://img.shields.io/badge/YouTube-Sujeito%20Programador-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCLc5Bq2yfs-S3Zse3ZFRMEQ)

</div>

## 📑 Índice

- [Agentes de Programação](#-agentes-de-programação)
- [Frameworks de Agentes](#-frameworks-de-agentes)
- [Agentes de Navegador e Desktop](#-agentes-de-navegador-e-desktop)
- [Agentes de Voz](#-agentes-de-voz)
- [IA Criativa](#-ia-criativa)
- [Automação e Workflows](#-automação-e-workflows)
- [Suporte ao Cliente e CRM](#-suporte-ao-cliente-e-crm)
- [Dados e Pesquisa](#-dados-e-pesquisa)
- [Memória para Agentes](#-memória-para-agentes)
- [IA Local e Self-Hosted](#-ia-local-e-self-hosted)
- [Agentes Autônomos Pessoais (comunidade)](#-agentes-autônomos-pessoais-comunidade)
- [Plataformas Multi-Agente](#-plataformas-multi-agente)
- [Ferramentas e Integrações (MCP)](#-ferramentas-e-integrações-mcp)
- [Protocolos e Padrões](#-protocolos-e-padrões)
- [Observabilidade e Avaliação](#-observabilidade-e-avaliação)
- [Modelos Open-Source para Agentes](#-modelos-open-source-para-agentes)
- [Segurança, Guardrails e Governança](#-segurança-guardrails-e-governança)

---

## 💻 Agentes de Programação

### IDEs com IA integrada

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Cursor](https://cursor.com) | Fork do VS Code. Modo Composer para edições em múltiplos arquivos. Suporte a vários modelos. | Grátis / pago |
| [GitHub Copilot](https://github.com/features/copilot) | Modo agente no VS Code. Do issue ao PR com o Copilot Workspace. Multimodelo. | Pago |
| [Devin (windsurf)](https://devin.ai/) | Modo agêntico Cascade. Memória de projeto. Agentes paralelos. | Grátis / pago |
| [JetBrains AI](https://www.jetbrains.com/ai/) | Integração profunda em todas as IDEs JetBrains. Autocompletar consciente de contexto. | Incluído na IDE |
| [Tabnine](https://www.tabnine.com/) | Foco em privacidade. Opção on-premise. Ajuste fino no seu código. | Grátis / pago |
| [Kiro](https://kiro.dev) | Desenvolvimento orientado a especificação: specs → tarefas → implementação. | Beta |

### Terminal e CLI

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | Agente CLI da Anthropic. Forte em raciocínio. Recurso de Agent Teams. | Assinatura / API |
| [OpenAI Codex CLI](https://github.com/openai/codex) | Agente de terminal da OpenAI. SDK de agentes. Multi-agente. | Assinatura |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Agente de terminal open-source do Google. Loop ReAct. Suporte a MCP. Apache 2.0. | Grátis (conta Google) |
| [Aider](https://github.com/paul-gauthier/aider) | Par de programação OSS. Integrado ao Git. Qualquer LLM. | Grátis + API |
| [Cline](https://github.com/cline/cline) | Extensão do VS Code. Acesso total a terminal e navegador. | Grátis + API |
| [OpenCode](https://github.com/opencode-ai/opencode) | Agente de terminal BYOK. | Grátis + API |

### Revisão de código e segurança

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Qodo](https://www.qodo.ai/) | Revisão de código com IA. Validação de PR consciente de contexto. | Grátis / empresarial |
| [CodeRabbit](https://coderabbit.ai/) | Revisor de PR com IA. Sugestões inline e segurança. | Grátis OSS / pago |
| [Snyk Code](https://snyk.io/) | Scanner de segurança com IA. Detecção de vulnerabilidades em tempo real. | Grátis / empresarial |
| [PR-Agent](https://github.com/Codium-ai/pr-agent) | Revisor de PR OSS. Descreve, revisa e melhora automaticamente. | Grátis (OSS) |

### App builders (prompt → app)

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Bolt.new](https://bolt.new) | Do prompt a um app web full-stack no navegador. | Grátis / pago |
| [Lovable](https://lovable.dev) | Descreva, construa e faça deploy a partir do chat. | Grátis / pago |
| [v0 (Vercel)](https://v0.dev) | Do prompt a componentes React/Tailwind. | Grátis / Pro |
| [Replit Agent](https://replit.com) | Full-stack a partir de prompt. Deploy automático. | Grátis / pago |
| [Dyad](https://github.com/dyad-sh/dyad) | OSS. Local-first. App builder no-code. | Grátis (OSS) |

---

## 🧱 Frameworks de Agentes

### Uso geral

| Framework | Linguagem | Descrição |
|-----------|-----------|-----------|
| [AI SDK](https://github.com/langchain-ai/langchain) | JS/TS | SDK de IA padroniza a integração de modelos de inteligência artificial (IA) entre os provedores compatíveis. |
| [LangChain](https://github.com/langchain-ai/langchain) | Py/JS | O mais adotado. Arquitetura modular, memória e ferramentas. |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Py/JS | Orquestração baseada em grafos. Grafos direcionados com estado. |
| [LlamaIndex](https://github.com/run-llama/llama_index) | Py/JS | Focado em dados. Ótimo para agentes RAG. |
| [Haystack](https://github.com/deepset-ai/haystack) | Py | Baseado em pipelines. Busca e recuperação. |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | C#/Py/Java | Empresarial, da Microsoft. Integração com Azure. |
| [Pydantic AI](https://github.com/pydantic/pydantic-ai) | Py | Type-safe. API pythônica limpa. Pronto para produção. |
| [DSPy](https://github.com/stanfordnlp/dspy) | Py | Stanford. Programar em vez de "promptar". Auto-otimização. |
| [Mastra](https://github.com/mastra-ai/mastra) | TS | TypeScript-first. Memória observacional. Apache 2.0. |
| [Google ADK](https://github.com/google/adk-python) | Py | Agent Development Kit do Google. Nativo do Gemini. Orquestração multi-agente. |

### Orquestração multi-agente

| Framework | Linguagem | Descrição |
|-----------|-----------|-----------|
| [AutoGen](https://github.com/microsoft/autogen) | Py | Conversas multi-agente da Microsoft. |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Py | Membros de "crew" baseados em papéis, com metas e ferramentas. |
| [MetaGPT](https://github.com/geekan/MetaGPT) | Py | Papéis de PM, arquiteto e engenheiro. Simula uma empresa de software. |
| [Strands Agents](https://github.com/strands-agents/sdk-python) | Py | Apoiado pela AWS. Uso de ferramentas orientado a modelo. |
| [CAMEL](https://github.com/camel-ai/camel) | Py | Simulação baseada em papéis. Raciocínio colaborativo. |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Py | Pioneiro. Hoje uma plataforma com construtor visual. |
| [AgentScope](https://github.com/modelscope/agentscope) | Py | Framework multi-agente da Alibaba. |

### Leves / minimalistas

| Framework | Linguagem | Descrição |
|-----------|-----------|-----------|
| [Smolagents](https://github.com/huggingface/smolagents) | Py | Agentes mínimos da HuggingFace. ~1000 linhas. |
| [Agno](https://github.com/agno-agi/agno) | Py | Leve e agnóstico a modelo. |
| [Upsonic](https://github.com/upsonic/upsonic) | Py | Suporte a MCP. Configuração mínima. |
| [Portia AI](https://github.com/portia-ai/portia-sdk-python) | Py | Agentes confiáveis em produção. |

---

## 🌐 Agentes de Navegador e Desktop

### Infraestrutura para desenvolvedores

| Ferramenta | Descrição |
|------------|-----------|
| [Browser Use](https://github.com/browser-use/browser-use) | Biblioteca OSS de agente de navegador. |
| [Skyvern](https://github.com/Skyvern-AI/skyvern) | Navegação orientada por visão, sem seletores codificados. |
| [Agent S2 (Simular)](https://github.com/simular-ai/Agent-S) | Framework OSS de automação de GUI. |
| [Browserbase](https://browserbase.com) | Infra de navegador na nuvem para agentes. Headless em escala. |
| [Playwright MCP](https://github.com/microsoft/playwright-mcp) | Servidor MCP para Playwright + agentes de IA. |
| [Scrapling](https://github.com/d4vinci/Scrapling) | Uma estrutura adaptativa de Web Scraping que lida com tudo, desde uma única solicitação até uma coleta completa |

---

## 🎙 Agentes de Voz

### Plataformas e APIs

| Plataforma | Descrição | Preço |
|------------|-----------|-------|
| [ElevenLabs](https://elevenlabs.io) | Referência do setor. IA conversacional com RAG, multimodal e batch calling. | Grátis / pago |
| [Vapi](https://vapi.ai) | Focado em desenvolvedores. Baixa latência, agnóstico a modelo. | Por uso |
| [Bland AI](https://bland.ai) | Automação de chamadas outbound. Integração com CRM. | Por uso |
| [Voiceflow](https://voiceflow.com) | Construtor no-code de voz e chat. Arrastar e soltar. | Grátis / pago |
| [Retell AI](https://retellai.com) | Agentes de voz realistas. Multilíngue. Telefonia. | Por uso |
| [Deepgram](https://deepgram.com) | APIs de STT e TTS. Baixa latência. | Por uso |
| [AssemblyAI](https://assemblyai.com) | STT com diarização, sentimento e sumarização. | Por uso |

### Voz open-source

| Ferramenta | Descrição |
|------------|-----------|
| [LiveKit Agents](https://github.com/livekit/agents) | Agentes de voz/vídeo em tempo real, OSS. |
| [Rasa](https://github.com/RasaHQ/rasa) | IA conversacional OSS. Self-hosted. Treino de NLU. |
| [Pipecat](https://github.com/pipecat-ai/pipecat) | IA conversacional de voz e multimodal, OSS. |
| [Vocode](https://github.com/vocodedev/vocode-python) | Agentes de voz baseados em LLM, OSS. |

---

## 🎨 IA Criativa

### Geração de imagem

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Fal.AI](https://fal.ai/) | Ferramenta com vários modelos para geração de imagem / video | Pago |
| [Runware](https://runware.ai/) | Ferramenta com vários modelos para geração de imagem / video | Pago |
| [Midjourney](https://midjourney.com) | Alta qualidade artística. Estética diferenciada. Discord + web. | Pago |
| [DALL·E](https://openai.com/dall-e) | Forte compreensão de prompt. Bom com texto na imagem. | Assinatura |
| [FLUX](https://blackforestlabs.ai) | Open-weight. Foco em fotorrealismo. | Grátis / API |
| [Stable Diffusion](https://stability.ai) | Open-source. Ecossistema ControlNet, LoRAs e ComfyUI. | Grátis (OSS) |
| [Adobe Firefly](https://firefly.adobe.com) | Treinado com dados licenciados. Integrado ao Photoshop. | Adobe CC |
| [Google Imagen](https://deepmind.google) | Fotorrealismo de ponta. API via AI Studio. | API |
| [Ideogram](https://ideogram.ai) | Melhor para texto dentro da imagem. Logos e pôsteres. | Grátis / pago |
| [Leonardo AI](https://leonardo.ai) | Multimodelo. Canvas em tempo real. Assets 3D para jogos. | Grátis / pago |

### Geração de vídeo

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Google Veo](https://deepmind.google) | Áudio + vídeo nativos. Alta resolução. | API |
| [Kling](https://klingai.com) | Realismo cinematográfico. Consistência de personagem. | Grátis / pago |
| [Runway](https://runwayml.com) | Motion Brush, Director Mode. Forte em edição. | Pago |
| [Sora](https://sora.com) | Da OpenAI. Coerência narrativa e física realista. | Assinatura |
| [Pika](https://pika.art) | Amigável para iniciantes. Renders rápidos. | Grátis / pago |
| [Luma Dream Machine](https://lumalabs.ai) | Alta resolução. Simulação de física. 3D/cinematográfico. | Pago |
| [Wan](https://github.com/Wan-Video/Wan2.1) | Melhor geração de vídeo OSS gratuita. Self-hostable. | Grátis (OSS) |
| [HunyuanVideo](https://github.com/Tencent/HunyuanVideo) | OSS da Tencent. Roda em GPU de consumidor. | Grátis (OSS) |
| [LTX Video](https://github.com/Lightricks/LTX-Video) | OSS. Dados licenciados. Termos comerciais claros. | Grátis (OSS) |

### Música e áudio

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Suno](https://suno.ai) | Texto para música. Faixas completas com vocais. | Grátis / pago |
| [Udio](https://udio.com) | Geração de música em alta fidelidade. Controle fino. | Grátis / pago |
| [Stable Audio](https://stableaudio.com) | Alta qualidade. Licença comercial. | Grátis / pago |
| [Meta AudioCraft](https://github.com/facebookresearch/audiocraft) | OSS. MusicGen + AudioGen. | Grátis (OSS) |

### 3D e design

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Meshy](https://meshy.ai) | Texto/imagem para 3D. Assets de jogos e produtos. | Grátis / pago |
| [Tripo AI](https://tripo3d.ai) | 3D rápido a partir de texto/imagens. Vários formatos. | Grátis / pago |
| [Vizcom](https://vizcom.ai) | Renderização com IA em tempo real para designers industriais. | Pago |

---

## ⚡ Automação e Workflows

### Automação

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [n8n](https://github.com/n8n-io/n8n) | Automação de workflows OSS com nós de agente de IA. Visual + código. | Grátis / nuvem |
| [Zapier AI](https://zapier.com/ai) | Milhares de apps. Workflows em linguagem natural. | Pago |
| [Make](https://make.com) | Plataforma visual de workflows com recursos de IA. | Grátis / pago |
| [Activepieces](https://github.com/activepieces/activepieces) | Alternativa OSS ao Zapier, com IA. | Grátis (OSS) |
| [Temporal](https://github.com/temporalio/temporal) | Execução durável para workflows de agentes de longa duração. | Grátis / nuvem |
| [Oh My Hermes](https://github.com/rlaope/oh-my-hermes) | Plugin de workflows para Hermes Agent. Memória de projeto revisada, modelos por tarefa e skills de pesquisa, planejamento e revisão de código. Requer Hermes Agent. | Grátis (OSS); custos de modelos à parte |

### Construtores no-code de agentes

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Dify](https://github.com/langgenius/dify) | LLMOps OSS. Construtor visual de agentes. RAG. | Grátis / nuvem |
| [Flowise](https://github.com/FlowiseAI/Flowise) | Construtor de agentes LLM OSS, arrastar e soltar. | Grátis (OSS) |
| [Langflow](https://github.com/langflow-ai/langflow) | Construtor visual multi-agente e RAG. | Grátis / nuvem |
| [Lindy](https://lindy.ai) | Agentes no-code. Muitas integrações. | Pago |
| [Relevance AI](https://relevanceai.com) | Agentes no-code para vendas, suporte e pesquisa. | Grátis / pago |

---

## 💼 Suporte ao Cliente e CRM

### Agentes de suporte

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Intercom Fin](https://intercom.com) | Resolve boa parte dos tickets. Aprende com a central de ajuda. | Pago |
| [Zendesk AI](https://zendesk.com) | Roteamento de tickets, detecção de sentimento, Answer Bot. | Pago |
| [Ada](https://ada.cx) | Resolução autônoma. Multicanal. | Empresarial |
| [Freshdesk Freddy AI](https://freshworks.com) | Triagem automática, roteamento e análise preditiva. | Pago |

---

## 📊 Dados e Pesquisa

### Deep research

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Claude Deep Research](https://claude.ai) | Investigação em várias etapas com citações. | Assinatura |
| [ChatGPT Deep Research](https://chat.openai.com) | Raciocínio estendido, navegação web e relatórios. | Assinatura |
| [Gemini Deep Research](https://gemini.google.com) | Google Search e Knowledge Graph. | Assinatura |
| [Perplexity](https://perplexity.ai) | Busca com IA e modo de pesquisa profunda. Citações em tempo real. | Grátis / pago |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | Pesquisa autônoma abrangente, OSS. | Grátis (OSS) |
| [STORM](https://github.com/stanford-oval/storm) | Stanford. Escreve artigos no estilo Wikipédia do zero. | Grátis (OSS) |

### Análise de dados

| Ferramenta | Descrição | Preço |
|------------|-----------|-------|
| [Julius AI](https://julius.ai) | Suba CSV/Excel e pergunte em linguagem natural. | Grátis / pago |
| [Hex](https://hex.tech) | Plataforma colaborativa de dados. Análise com IA. | Grátis / pago |
| [PandasAI](https://github.com/Sinaptik-AI/pandas-ai) | Converse com seus dados. Linguagem natural para Pandas/SQL. | Grátis (OSS) |
| [TaskWeaver](https://github.com/microsoft/TaskWeaver) | Microsoft. Agentes de análise de dados code-first. | Grátis (OSS) |

### RAG e bases de conhecimento

| Ferramenta | Descrição |
|------------|-----------|
| [RAGFlow](https://github.com/infiniflow/ragflow) | Motor RAG OSS com capacidades de agente. |
| [Chroma](https://github.com/chroma-core/chroma) | Banco de embeddings OSS. Rápido para construir RAG. |
| [Weaviate](https://github.com/weaviate/weaviate) | Vector DB OSS. GraphQL. Busca multimodal. |
| [Qdrant](https://github.com/qdrant/qdrant) | Vector DB de alta performance em Rust. |
| [Milvus](https://github.com/milvus-io/milvus) | Vector DB cloud-native. Escala de bilhões. |
| [Pinecone](https://pinecone.io) | Vector DB gerenciado. Serverless. Baixa latência. |

---

## 🧠 Memória para Agentes

| Ferramenta | Descrição |
|------------|-----------|
| [Mem0](https://github.com/mem0ai/mem0) | Camada de memória para agentes. Longo prazo entre sessões. Autohospedável ou gerenciado. |
| [Zep](https://github.com/getzep/zep) | Memória de longo prazo com grafo de conhecimento temporal. Foco em produção. |
| [Letta (MemGPT)](https://github.com/letta-ai/letta) | Agentes com estado e memória persistente. Sucessor do MemGPT. |
| [Cognee](https://github.com/topoteretes/cognee) | Memória para agentes combinando grafos de conhecimento e vetores (ECL). |

---

## 🏠 IA Local e Self-Hosted

### Executores de LLM local

| Ferramenta | Descrição |
|------------|-----------|
| [Ollama](https://github.com/ollama/ollama) | Rode LLMs localmente. CLI simples. |
| [llama.cpp](https://github.com/ggml-org/llama.cpp) | Inferência em C/C++. CPU, GPU e Apple Silicon. |
| [vLLM](https://github.com/vllm-project/vllm) | Serving de alto throughput. PagedAttention. Produção. |
| [LM Studio](https://lmstudio.ai) | App desktop para LLMs locais. UI amigável. |
| [Jan](https://github.com/janhq/jan) | Alternativa OSS ao ChatGPT. 100% offline. |
| [LocalAI](https://github.com/mudler/LocalAI) | Substituto drop-in da API da OpenAI. Sem GPU obrigatória. |
| [GPT4All](https://github.com/nomic-ai/gpt4all) | Chat local OSS. Roda em hardware de consumidor. |
| [Llamafile](https://github.com/Mozilla-Ocho/llamafile) | LLMs como um único arquivo. Zero setup. Mozilla. |

### Provedores de inferência rápida

| Ferramenta | Descrição |
|------------|-----------|
| [Groq Cloud](https://console.groq.com) | Inferência ultrarrápida em LPU. Camada gratuita. |
| [Cerebras Inference](https://inference.cerebras.ai) | Inferência de LLM muito rápida. Camada gratuita. |
| [Fireworks AI](https://fireworks.ai) | Inferência serverless. Fine-tuning e RAG. | 
| [Together AI](https://together.ai) | Centenas de modelos abertos. API de inferência rápida. |

### Agentes e UIs self-hosted

| Ferramenta | Descrição |
|------------|-----------|
| [Open WebUI](https://github.com/open-webui/open-webui) | UI self-hosted estilo ChatGPT. Controle de acesso e extensões. |
| [LibreChat](https://github.com/danny-avila/LibreChat) | Chat multimodelo self-hosted. Todos os principais provedores. |
| [LobeChat](https://github.com/lobehub/lobe-chat) | UI OSS estilo ChatGPT/Gemini. Sistema de plugins. Multimodal. |
| [Anything LLM](https://github.com/Mintplex-Labs/anything-llm) | App all-in-one. RAG e agentes. Desktop + Docker. |
| [DB-GPT](https://github.com/eosphoros-ai/DB-GPT) | Interação com dados usando LLM local. 100% privado. |

---

## 🐙 Agentes Autônomos Pessoais (comunidade)


| Agente | Descrição | Preço |
|--------|-----------|-------|
| [OpenClaw](https://github.com/openclaw/openclaw) | Agente de IA open-source e self-hosted. Roda na sua máquina e conecta a WhatsApp, Telegram, Discord, Signal, Slack e dezenas de integrações, sem rotear seus dados por uma API de terceiros. Um dos repositórios de crescimento mais rápido do GitHub. MIT. | Grátis (OSS) |
| [Hermes Agent](https://github.com/NousResearch/hermes-agent) | Agente autônomo da Nous Research. Roda no terminal, app desktop, mensageiros e IDEs. Cria "skills" próprias após tarefas complexas para reutilizá-las depois. Compatível com vários provedores de LLM e modelos locais. | Grátis (OSS) |
| [Grok Bot](https://x.ai/bot) | Plataforma no-code de múltiplos agentes. Cada bot com seu próprio ambiente e memória, com handoff automático entre eles. | Pago |
| [Zero Claw](https://github.com/zeroclaw-labs/zeroclaw) | Infraestrutura de assistente pessoal de IA rápida, compacta e totalmente autônoma, compatível com qualquer sistema operacional. | Pago |

---

## 🤝 Plataformas Multi-Agente

| Plataforma | Descrição | Preço |
|------------|-----------|-------|
| [ChatGPT](https://chat.openai.com) | GPTs, Deep Research, Canvas, modo agente e visão. | Grátis / pago |
| [Claude](https://claude.ai) | Uso de ferramentas, controle de computador, MCP e execução de código. | Grátis / pago |
| [Gemini](https://gemini.google.com) | Deep Think, Gems, multimodal. Ecossistema Google. | Grátis / pago |
| [Grok](https://x.ai) | Dados em tempo real do X. Geração de imagem. | Assinatura |
| [Meta AI](https://meta.ai) | Baseado em Llama. WhatsApp/Messenger. | Grátis |
| [Microsoft Copilot](https://copilot.microsoft.com) | Integração com Office 365. Empresarial. | Grátis / pago |
| [Coze](https://coze.com) | Construtor de agentes da ByteDance. Workflow visual. Marketplace de plugins. | Grátis / pago |

---

## 🔌 Ferramentas e Integrações (MCP)

| Ferramenta | Descrição |
|------------|-----------|
| [Composio](https://github.com/ComposioHQ/composio) | Centenas de integrações e ações prontas para agentes, com autenticação gerenciada. |
| [Firecrawl](https://github.com/mendableai/firecrawl) | Transforma sites em dados limpos (Markdown/JSON) prontos para LLMs. |
| [Tavily](https://tavily.com) | API de busca na web pensada para agentes e RAG. |
| [Exa](https://exa.ai) | Busca semântica na web voltada para IA. |
| [Apify](https://apify.com) | Plataforma de scraping e automação web, com atores e integração MCP. |

---

## 📡 Protocolos e Padrões

| Protocolo | Descrição |
|-----------|-----------|
| [MCP (Model Context Protocol)](https://github.com/modelcontextprotocol) | Padrão aberto da Anthropic. "USB-C para IA". Padrão do setor para ferramentas de agentes. |
| [A2A (Agent-to-Agent)](https://github.com/google/A2A) | Protocolo do Google para comunicação entre agentes. |
| [OpenAI Function Calling](https://platform.openai.com/docs/guides/function-calling) | Uso de ferramentas nativo da OpenAI. Schema JSON. |
| [Tool Use (Anthropic)](https://docs.anthropic.com/en/docs/build-with-claude/tool-use) | Uso de ferramentas nativo do Claude. JSON estruturado. |
| [OpenAPI](https://github.com/OAI/OpenAPI-Specification) | Especificação de API padrão do setor. Base para ferramentas de agentes. |

---

## 🔍 Observabilidade e Avaliação

### Tracing e monitoramento

| Ferramenta | Descrição |
|------------|-----------|
| [Langfuse](https://github.com/langfuse/langfuse) | Observabilidade de LLM OSS. Traces, evals e prompts. |
| [LangSmith](https://smith.langchain.com) | Plataforma da LangChain. Tracing, testes e avaliação. |
| [Arize Phoenix](https://github.com/Arize-ai/phoenix) | Observabilidade de IA OSS. Traces, evals e embeddings. |
| [Helicone](https://github.com/Helicone/helicone) | Observabilidade de LLM OSS. Integração em uma linha. |
| [Braintrust](https://braintrustdata.com) | Desenvolvimento orientado a avaliação. Rastreio de experimentos. |

### Benchmarks

| Benchmark | Descrição |
|-----------|-----------|
| [SWE-bench](https://github.com/princeton-nlp/SWE-bench) | Padrão do setor para agentes de programação. |
| [AgentBench](https://github.com/THUDM/AgentBench) | Benchmark de agentes LLM em 8 ambientes. |
| [GAIA](https://huggingface.co/gaia-benchmark) | Assistente de IA geral. Tarefas do mundo real. |
| [WebArena](https://github.com/web-arena-x/webarena) | Benchmark de agentes web em sites reais. |

---

## 🧠 Modelos Open-Source para Agentes

| Modelo | Org | Destaques |
|--------|-----|-----------|
| [Llama](https://github.com/meta-llama) | Meta | Contexto longo. Forte uso de ferramentas. Open-weight. |
| [Qwen](https://github.com/QwenLM/Qwen3) | Alibaba | Foco agêntico. Nativo de MCP. Multimodal. |
| [DeepSeek](https://github.com/deepseek-ai/DeepSeek-V3) | DeepSeek | Custo baixo. Forte em raciocínio. |
| [Gemma](https://github.com/google-deepmind/gemma) | Google | Modelos eficientes para consumidor/IoT. |
| [GLM](https://github.com/THUDM/GLM-4) | Zhipu | Baixa taxa de alucinação. Forte em código. |
| [Mistral](https://mistral.ai) | Mistral | Function calling, modo JSON. Europeu. |
| [Command R+](https://cohere.com) | Cohere | Otimizado para RAG e uso empresarial de ferramentas. |

---

## 🛡 Segurança, Guardrails e Governança

### Guardrails

| Ferramenta | Descrição |
|------------|-----------|
| [Guardrails AI](https://github.com/guardrails-ai/guardrails) | Garantias de estrutura, tipo e qualidade para saídas de LLM. |
| [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) | NVIDIA. Guardrails programáveis de conversa. |
| [Lakera Guard](https://lakera.ai) | Proteção em tempo real. Injeção de prompt, vazamento e toxicidade. |

---

<div align="center">

Se esta lista te ajudou, deixe uma ⭐ e compartilhe!

<sub>[@sujeitoprogramador](https://www.instagram.com/sujeitoprogramador/)</sub>

</div>
