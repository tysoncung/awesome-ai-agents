# Awesome AI Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome AI agents, LLM frameworks, autonomous agent systems, and multi-agent orchestration tools for building intelligent applications.

AI agents are autonomous systems powered by large language models (LLMs) that can perceive, reason, plan, and act to achieve goals. This list covers frameworks, tools, and resources for building production-ready AI agent systems.

## Contents

- [Multi-Agent Frameworks](#multi-agent-frameworks)
- [Agent Orchestration](#agent-orchestration)
- [LLM Integration](#llm-integration)
- [Tool & Function Calling](#tool--function-calling)
- [Memory & State Management](#memory--state-management)
- [Agent Development Platforms](#agent-development-platforms)
- [Production & Deployment](#production--deployment)
- [Learning Resources](#learning-resources)
- [Research Papers](#research-papers)

## Multi-Agent Frameworks

### Agent Collaboration
- [AutoGen](https://github.com/microsoft/autogen) - Microsoft's framework for building multi-agent conversational systems.
- [CrewAI](https://github.com/joaomdmoura/crewAI) - Cutting-edge framework for orchestrating role-playing autonomous AI agents.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Build stateful multi-actor applications with LLMs using graph-based workflows.
- [Swarm](https://github.com/openai/swarm) - OpenAI's educational framework for exploring lightweight multi-agent orchestration.
- [AgentScope](https://github.com/modelscope/agentscope) - Easier multi-agent application development with LLMs.

### Autonomous Agents
- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Experimental autonomous GPT-4 agent that chains tasks.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - AI-powered task management system using OpenAI and vector databases.
- [GPT Engineer](https://github.com/gpt-engineer-org/gpt-engineer) - Specify what you want to build, AI asks clarifying questions, then builds it.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent framework that assigns different roles to GPTs to form collaborative software entities.

## Agent Orchestration

### Workflow & Planning
- [LangChain](https://github.com/langchain-ai/langchain) - Building applications with LLMs through composability.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs with conventional programming languages.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end framework for building production-ready LLM applications.
- [Composio](https://github.com/ComposioHQ/composio) - Integration platform for AI agents with 150+ tools.

### Task Management
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) - Code-first framework for building LLM-powered autonomous agents.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Assemble, configure, and deploy autonomous AI agents in your browser.
- [ix](https://github.com/kreneskyp/ix) - Autonomous GPT-4 agent platform.

## LLM Integration

### Model Providers
- [OpenAI API](https://platform.openai.com/docs/guides/gpt) - GPT-4, GPT-3.5 Turbo with function calling.
- [Anthropic Claude](https://www.anthropic.com/claude) - Claude 3 Opus, Sonnet, Haiku with extended context.
- [Google Gemini](https://ai.google.dev/) - Multimodal AI model with function calling.
- [Ollama](https://ollama.ai/) - Run open-source LLMs locally (Llama 3, Mistral, etc.).
- [vLLM](https://github.com/vllm-project/vllm) - High-throughput LLM serving with PagedAttention.

### Agent-Specific Models
- [Gorilla](https://github.com/ShishirPatil/gorilla) - LLM connected with massive APIs.
- [ToolLLM](https://github.com/OpenBMB/ToolLLM) - Facilitating large language models to master 16000+ real-world APIs.

## Tool & Function Calling

### Function Calling Frameworks
- [OpenAI Functions](https://platform.openai.com/docs/guides/function-calling) - Native function calling in GPT-4 and GPT-3.5.
- [LangChain Tools](https://python.langchain.com/docs/modules/agents/tools/) - Pre-built tools for agents.
- [Transformers Agents](https://huggingface.co/docs/transformers/transformers_agents) - Hugging Face toolkit for building agents.

### Tool Integration
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation with AI capabilities and 400+ integrations.
- [Zapier AI Actions](https://actions.zapier.com/) - Expose Zapier actions to LLMs.
- [Flowise](https://github.com/FlowiseAI/Flowise) - Visual builder for AI workflows.

## Memory & State Management

### Vector Databases
- [Pinecone](https://www.pinecone.io/) - Vector database for LLM applications.
- [Weaviate](https://github.com/weaviate/weaviate) - Open-source vector search engine.
- [Qdrant](https://github.com/qdrant/qdrant) - Vector similarity search engine with extended filtering support.
- [Chroma](https://github.com/chroma-core/chroma) - Open-source embedding database.
- [Milvus](https://github.com/milvus-io/milvus) - Cloud-native vector database.

### Memory Systems
- [Mem0](https://github.com/mem0ai/mem0) - Memory layer for AI agents.
- [Zep](https://github.com/getzep/zep) - Long-term memory for AI assistants.
- [LangMem](https://github.com/langchain-ai/langmem) - Memory management for LangChain agents.

## Agent Development Platforms

### Low-Code/No-Code
- [Flowise](https://github.com/FlowiseAI/Flowise) - Drag-and-drop UI to build LLM flows.
- [Dify](https://github.com/langgenius/dify) - LLMOps platform for building AI applications.
- [PromptFlow](https://github.com/microsoft/promptflow) - Streamlining development cycle of LLM applications.
- [Botpress](https://github.com/botpress/botpress) - Open-source conversational AI platform.

### Full-Stack Platforms
- [LangSmith](https://www.langchain.com/langsmith) - Platform for debugging, testing, and monitoring LLM applications.
- [Weights & Biases](https://wandb.ai/) - Developer tools for ML experiment tracking.
- [MLflow](https://mlflow.org/) - Platform for ML lifecycle management.

## Production & Deployment

### Serving & Scaling
- [Ray](https://github.com/ray-project/ray) - Distributed computing framework for ML workloads.
- [BentoML](https://github.com/bentoml/BentoML) - Unified framework for building, shipping, and scaling ML services.
- [Seldon Core](https://github.com/SeldonIO/seldon-core) - ML deployment on Kubernetes.

### Monitoring & Observability
- [LangFuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform.
- [Phoenix](https://github.com/Arize-ai/phoenix) - AI observability & evaluation.
- [Helicone](https://www.helicone.ai/) - Open-source LLM observability platform.

## Learning Resources

### Courses & Tutorials
- [DeepLearning.AI Courses](https://www.deeplearning.ai/courses/) - AI agent development courses.
- [LangChain Academy](https://academy.langchain.com/) - Official LangChain learning platform.
- [Microsoft Learn](https://learn.microsoft.com/en-us/semantic-kernel/) - Semantic Kernel tutorials.

### Books
- [Building LLM Apps](https://www.oreilly.com/library/view/building-llm-apps/9781098150952/) - O'Reilly guide to LLM application development.
- [Prompt Engineering Guide](https://www.promptingguide.ai/) - Comprehensive prompt engineering resource.

### Communities
- [LangChain Discord](https://discord.gg/langchain) - LangChain community.
- [AutoGPT Discord](https://discord.gg/autogpt) - AutoGPT development community.
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) - Subreddit for local LLM deployment.

## Research Papers

- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) - Foundation for agent reasoning patterns.
- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761) - Self-taught tool use.
- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) - Stanford's agent simulation research.
- [AutoGPT: An Autonomous GPT-4 Experiment](https://github.com/Significant-Gravitas/AutoGPT) - Foundational autonomous agent work.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
