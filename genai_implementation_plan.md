# 🤖 GenAI Mastery Curriculum — From Zero to Production-Ready (2026 Edition)

> **Philosophy**: "Build first, understand deeper, then master." Every chapter starts with a working demo, then unpacks the WHY.

---

## 🎯 Who Is This For?

| Aspect | Details |
|--------|---------|
| **Target Learner** | Developers who want to build with LLMs, crack GenAI interviews, and ship production AI apps |
| **Prerequisites** | Basic Python (functions, classes, pip). No ML/AI background needed |
| **Outcome** | Interview-ready + Can build production GenAI apps with LangChain, LangGraph, RAG, Agents |
| **Time Estimate** | ~30-40 hours of focused learning across 10 chapters |
| **Language** | Python (100% hands-on, every concept has runnable code) |

---

## 📚 Teaching Methodology

Every module follows the **BUILD → UNDERSTAND → MASTER** cycle:

| Phase | Name | What Happens |
|-------|------|-------------|
| 1️⃣ | **🔥 Quick Win** | Start with a working demo — "Look what you just built!" |
| 2️⃣ | **🧠 Deep Dive** | Now understand WHY it works — concepts, architecture, mental models |
| 3️⃣ | **🛠️ Hands-On** | Build progressively harder projects with the concept |
| 4️⃣ | **💡 Interview Prep** | Common interview questions + how to answer them |
| 5️⃣ | **🚀 Build Something Real** | Mini-project that consolidates everything |

---

## 📁 Complete Course Structure

```
GENAI_MASTERY_NOTES/
├── README.md                              # Master guide & learning path
│
├── chapter_01_foundations/                 # What is GenAI? LLMs? How do they work?
│   ├── module_01_genai_landscape/
│   │   ├── 01a_concept_what_is_genai.ipynb
│   │   └── 01b_hands_on_first_llm_call.ipynb
│   └── module_02_how_llms_work/
│       ├── 02a_concept_transformers_intuition.ipynb
│       └── 02b_hands_on_tokenization_embeddings.ipynb
│
├── chapter_02_prompt_engineering/          # The art & science of talking to LLMs
│   ├── module_01_prompt_basics/
│   │   ├── 01a_concept_prompt_anatomy.ipynb
│   │   └── 01b_hands_on_prompt_patterns.ipynb
│   └── module_02_advanced_prompting/
│       ├── 02a_concept_cot_react_tot.ipynb
│       └── 02b_hands_on_structured_outputs.ipynb
│
├── chapter_03_langchain_core/             # The backbone framework
│   ├── module_01_lc_fundamentals/
│   │   ├── 01a_concept_langchain_architecture.ipynb
│   │   └── 01b_hands_on_models_prompts_chains.ipynb
│   ├── module_02_chains_and_runnables/
│   │   ├── 02a_concept_lcel_runnables.ipynb
│   │   └── 02b_hands_on_building_chains.ipynb
│   └── module_03_tools_and_output_parsers/
│       ├── 03a_concept_tools_parsers.ipynb
│       └── 03b_hands_on_function_calling.ipynb
│
├── chapter_04_embeddings_vector_stores/   # The foundation of RAG
│   ├── module_01_embeddings/
│   │   ├── 01a_concept_what_are_embeddings.ipynb
│   │   └── 01b_hands_on_embedding_models.ipynb
│   └── module_02_vector_databases/
│       ├── 02a_concept_vector_search.ipynb
│       └── 02b_hands_on_chromadb_faiss.ipynb
│
├── chapter_05_rag/                        # Retrieval-Augmented Generation
│   ├── module_01_basic_rag/
│   │   ├── 01a_concept_rag_architecture.ipynb
│   │   └── 01b_hands_on_first_rag_pipeline.ipynb
│   ├── module_02_advanced_rag/
│   │   ├── 02a_concept_chunking_retrieval.ipynb
│   │   └── 02b_hands_on_hybrid_search_reranking.ipynb
│   └── module_03_production_rag/
│       ├── 03a_concept_rag_evaluation.ipynb
│       └── 03b_project_enterprise_rag_chatbot.ipynb
│
├── chapter_06_agents_fundamentals/        # AI Agents 101
│   ├── module_01_what_are_agents/
│   │   ├── 01a_concept_agents_tools_reasoning.ipynb
│   │   └── 01b_hands_on_react_agent.ipynb
│   └── module_02_tool_calling/
│       ├── 02a_concept_function_calling.ipynb
│       └── 02b_hands_on_custom_tools.ipynb
│
├── chapter_07_langgraph/                  # Stateful multi-step agents
│   ├── module_01_lg_fundamentals/
│   │   ├── 01a_concept_graphs_state_nodes.ipynb
│   │   └── 01b_hands_on_first_graph.ipynb
│   ├── module_02_control_flow/
│   │   ├── 02a_concept_conditional_edges_loops.ipynb
│   │   └── 02b_hands_on_agent_with_tools.ipynb
│   └── module_03_advanced_langgraph/
│       ├── 03a_concept_persistence_hitl.ipynb
│       └── 03b_project_research_agent.ipynb
│
├── chapter_08_multi_agent_systems/        # Multiple agents working together
│   ├── module_01_multi_agent_patterns/
│   │   ├── 01a_concept_architectures.ipynb
│   │   └── 01b_hands_on_supervisor_pattern.ipynb
│   └── module_02_crewai_autogen/
│       ├── 02a_concept_framework_comparison.ipynb
│       └── 02b_hands_on_crew_of_agents.ipynb
│
├── chapter_09_finetuning_and_mcp/         # Customization & standards
│   ├── module_01_finetuning/
│   │   ├── 01a_concept_when_to_finetune.ipynb
│   │   └── 01b_hands_on_lora_qlora.ipynb
│   └── module_02_mcp_protocol/
│       ├── 02a_concept_model_context_protocol.ipynb
│       └── 02b_hands_on_building_mcp_server.ipynb
│
├── chapter_10_production_and_interviews/  # Ship it + crack the interview
│   ├── module_01_llmops/
│   │   ├── 01a_concept_deployment_monitoring.ipynb
│   │   └── 01b_hands_on_langsmith_eval.ipynb
│   ├── module_02_guardrails_safety/
│   │   ├── 02a_concept_safety_guardrails.ipynb
│   │   └── 02b_hands_on_input_output_validation.ipynb
│   └── module_03_interview_prep/
│       ├── 03a_interview_questions_answers.ipynb
│       └── 03b_system_design_genai.ipynb
│
└── capstone_projects/
    ├── project_01_rag_knowledge_assistant.ipynb
    ├── project_02_multi_agent_researcher.ipynb
    └── project_03_genai_saas_backend.ipynb
```

---

# 📖 DETAILED CHAPTER BREAKDOWN

---

## 🔷 CHAPTER 01: Foundations — What is GenAI & How LLMs Work

### Why This Chapter Matters
> Before you build with LLMs, you MUST understand what they are, what they can/can't do, and how they think. This is the #1 interview differentiator — everyone can use ChatGPT, but can you explain HOW it works?

### Module 01: The GenAI Landscape (2026)

**`01a_concept_what_is_genai.ipynb`**
```
🔥 QUICK WIN (5 min)
├── Make your first API call to an LLM
└── "You just talked to a robot brain with 3 lines of code!"

🧠 DEEP DIVE
├── What is Generative AI?
│   └── Analogy: Regular AI = Classifier (cat vs dog)
│   └── GenAI = Creator (draw me a cat riding a motorcycle)
│   └── The shift: from UNDERSTANDING to GENERATING
│
├── The LLM Family Tree (2026)
│   ├── Closed-Source (Frontier): GPT-4o, Claude 4, Gemini 2.5
│   ├── Open-Weights: Llama 3.3, Mistral, Qwen 2.5
│   └── When to use which? Cost vs Control vs Capability
│
├── Key Terminology Crash Course
│   ├── Tokens (not words!)
│   ├── Context Window (how much the LLM can "see")
│   ├── Temperature (creativity knob)
│   ├── Top-p / Top-k (sampling strategies)
│   ├── System Prompt vs User Prompt
│   └── Inference vs Training
│
└── The GenAI Stack in 2026
    ├── Models: OpenAI, Anthropic, Google, Open-source
    ├── Orchestration: LangChain, LangGraph
    ├── Retrieval: Vector DBs, Embeddings
    ├── Monitoring: LangSmith, Weights & Biases
    └── Deployment: Cloud APIs, Ollama (local)
```

**`01b_hands_on_first_llm_call.ipynb`**
```
🛠️ HANDS-ON
├── Setup: Install openai, langchain-openai, python-dotenv
├── Exercise 1: Call OpenAI API directly (raw requests)
├── Exercise 2: Call using LangChain ChatModel wrapper
├── Exercise 3: Play with temperature (0.0 vs 1.0 vs 2.0)
├── Exercise 4: System prompts — make the LLM act as different roles
├── Exercise 5: Token counting & cost estimation
│
💡 INTERVIEW PREP
├── Q: What's the difference between GPT-4 and GPT-4o?
├── Q: When would you choose open-source over API models?
├── Q: Explain tokens. Why aren't they words?
└── Q: What does temperature=0 mean?
```

### Module 02: How LLMs Actually Work

**`02a_concept_transformers_intuition.ipynb`**
```
🧠 DEEP DIVE (Intuition, NOT Math-heavy)
├── The Transformer Architecture (10,000-foot view)
│   └── Analogy: The LLM is a very sophisticated autocomplete
│   └── It predicts the NEXT TOKEN, one at a time
│   └── "The cat sat on the ___" → "mat" (highest probability)
│
├── Self-Attention: How LLMs "Read"
│   └── Analogy: Speed reading with highlighters
│   └── Each word "looks at" every other word
│   └── Decides which words are relevant to understanding each position
│   └── Simple visual: "The bank near the river" — "bank" attends to "river"
│
├── Embeddings: How LLMs "Think"
│   └── Words become numbers (vectors)
│   └── Similar meanings → nearby in vector space
│   └── king - man + woman ≈ queen (the famous example)
│
├── Training Pipeline Overview
│   ├── Pre-training: Read the internet → learn language patterns
│   ├── Instruction Tuning: Learn to follow instructions
│   └── RLHF/RLAIF: Learn from human preferences
│
├── Mixture of Experts (MoE)
│   └── Not all parameters active at once
│   └── Analogy: Hospital with specialists
│
└── Limitations & Hallucinations
    ├── Why LLMs make things up (probabilistic, not knowledge-based)
    ├── Knowledge cutoff problem
    └── Reasoning limitations
```

**`02b_hands_on_tokenization_embeddings.ipynb`**
```
🛠️ HANDS-ON
├── Exercise 1: Tokenize text with tiktoken
│   └── See how "Hello world" becomes [15339, 1917]
│   └── Surprise: "chatgpt" takes more tokens than you'd think!
├── Exercise 2: Generate embeddings with OpenAI
│   └── Embed sentences, calculate cosine similarity
│   └── See that "happy" is closer to "joyful" than to "banana"
├── Exercise 3: Build a simple semantic search
│   └── Embed 10 sentences → find the most similar to a query
├── Exercise 4: Visualize embeddings in 2D (using PCA)
│
💡 INTERVIEW PREP
├── Q: Explain the Transformer architecture in simple terms
├── Q: What is self-attention? Why is it important?
├── Q: What are embeddings? How do they capture meaning?
├── Q: Why do LLMs hallucinate? How do you mitigate it?
└── Q: What is RLHF?
```

---

## 🔷 CHAPTER 02: Prompt Engineering — Talking to LLMs Effectively

### Module 01: Prompt Anatomy & Basic Patterns
```
Topics:
├── Anatomy of a prompt (System, User, Assistant messages)
├── Zero-shot, One-shot, Few-shot prompting
├── Role prompting ("You are a senior Python developer...")
├── Template-based design with variables
├── Output formatting (JSON, tables, structured)
└── Hands-on: Build a product review analyzer
```

### Module 02: Advanced Prompting Techniques
```
Topics:
├── Chain-of-Thought (CoT) — "Think step by step"
├── Tree-of-Thought (ToT) — Explore multiple reasoning paths
├── ReAct Pattern — Reason + Act
├── Self-Consistency — Multiple samples, majority vote
├── Structured Outputs with Pydantic
├── Prompt injection attacks & defense
└── Hands-on: Build a multi-step reasoning system
```

---

## 🔷 CHAPTER 03: LangChain Core — The Framework

### Module 01: LangChain Fundamentals
```
Topics:
├── LangChain architecture (v0.3+ / 2026 version)
├── Chat Models (OpenAI, Anthropic, Google, Ollama)
├── Prompt Templates (ChatPromptTemplate)
├── Message types (System, Human, AI)
├── Simple chains
└── Hands-on: Build a translation chain
```

### Module 02: LCEL & Runnables
```
Topics:
├── LangChain Expression Language (LCEL)
├── The pipe operator "|" — composition
├── RunnablePassthrough, RunnableLambda, RunnableParallel
├── Streaming responses
├── Batch processing
└── Hands-on: Build a multi-step analysis pipeline
```

### Module 03: Tools & Output Parsers
```
Topics:
├── Output parsers (JSON, Pydantic, Structured)
├── Tool definition and binding
├── Function calling via LangChain
├── Custom tool creation
└── Hands-on: LLM that searches the web and answers
```

---

## 🔷 CHAPTER 04: Embeddings & Vector Stores

### Module 01: Embeddings Deep Dive
```
Topics:
├── What are vector embeddings (geometric intuition)
├── Embedding models (OpenAI, Sentence-Transformers, Cohere)
├── Cosine similarity, dot product, L2 distance
├── Dimensionality (768 vs 1536 vs 3072)
└── Hands-on: Build a semantic similarity engine
```

### Module 02: Vector Databases
```
Topics:
├── Why we need vector DBs (limitations of regular search)
├── ChromaDB (local, fast prototyping)
├── FAISS (Meta's library, high performance)
├── Pinecone (managed, production)
├── Weaviate (hybrid search)
├── Comparison table: When to use which?
└── Hands-on: Store and search 1000 documents
```

---

## 🔷 CHAPTER 05: RAG (Retrieval-Augmented Generation)

### Module 01: Basic RAG Pipeline
```
Topics:
├── What is RAG? Why do we need it?
├── The RAG Architecture (Load → Split → Embed → Store → Retrieve → Generate)
├── Document loaders (PDF, Web, CSV, Notion, etc.)
├── Text splitting strategies (recursive, semantic)
├── End-to-end pipeline
└── Hands-on: "Chat with your PDF" in 50 lines
```

### Module 02: Advanced RAG Techniques
```
Topics:
├── Chunking strategies (fixed, semantic, hierarchical)
├── Hybrid search (vector + keyword/BM25)
├── Query transformation & HyDE
├── Re-ranking (Cohere, Cross-Encoder)
├── Multi-query retrieval
├── Citation tracking
├── GraphRAG, Corrective RAG
└── Hands-on: Production-quality RAG with re-ranking
```

### Module 03: Production RAG
```
Topics:
├── Evaluating RAG (Faithfulness, Relevance, Context Precision)
├── RAG evaluation with RAGAS framework
├── Common failure modes & debugging
├── Metadata filtering & access control
└── PROJECT: Enterprise RAG Knowledge Bot
```

---

## 🔷 CHAPTER 06: AI Agents Fundamentals

### Module 01: What Are Agents?
```
Topics:
├── From Chains to Agents (the evolution)
├── Reasoning + Acting = ReAct framework
├── Agent architectures (plan-then-execute, iterative)
├── Memory types (buffer, summary, conversation)
└── Hands-on: Build a ReAct agent from scratch
```

### Module 02: Tool Calling & Function Calling
```
Topics:
├── Function calling API (OpenAI, Anthropic)
├── Tool definition schemas
├── Custom tools (API calls, DB queries, calculations)
├── Error handling & retries
└── Hands-on: Agent that queries a database and generates reports
```

---

## 🔷 CHAPTER 07: LangGraph — Stateful Agentic Workflows

### Module 01: LangGraph Fundamentals
```
Topics:
├── Why LangGraph? (limitations of linear chains)
├── Core concepts: State, Nodes, Edges
├── TypedDict state management
├── Building your first graph
├── Conditional edges
└── Hands-on: Chatbot with routing
```

### Module 02: Control Flow & Persistence
```
Topics:
├── Cycles and loops in graphs
├── Checkpointing and persistence
├── Human-in-the-Loop (interrupt/approve patterns)
├── Subgraphs and composition
└── Hands-on: Agent that searches, decides, and acts
```

### Module 03: Advanced LangGraph
```
Topics:
├── Multi-agent graphs
├── Streaming with LangGraph
├── Error handling and fallbacks
├── Deployment with LangGraph CLI
└── PROJECT: Autonomous Research Agent
```

---

## 🔷 CHAPTER 08: Multi-Agent Systems

### Module 01: Multi-Agent Architectures
```
Topics:
├── Supervisor pattern (one boss, many workers)
├── Hierarchical delegation
├── Collaborative vs competitive agents
├── Agent handoff patterns
└── Hands-on: Supervisor with specialist agents
```

### Module 02: CrewAI & Framework Comparison
```
Topics:
├── CrewAI: Agents, Tasks, Crews, Processes
├── AutoGen: Conversational agents
├── LangGraph multi-agent vs CrewAI vs AutoGen
├── When to use which?
└── Hands-on: Build a content creation crew
```

---

## 🔷 CHAPTER 09: Fine-Tuning & MCP Protocol

### Module 01: Fine-Tuning LLMs
```
Topics:
├── RAG vs Fine-tuning: When to use which?
├── LoRA & QLoRA (parameter-efficient fine-tuning)
├── Data preparation for fine-tuning
├── Fine-tuning with OpenAI API
├── Fine-tuning open-source models (Unsloth, HuggingFace)
└── Hands-on: Fine-tune a model for your domain
```

### Module 02: Model Context Protocol (MCP)
```
Topics:
├── What is MCP? (USB-C for AI)
├── Why standardize tool communication?
├── MCP architecture (Server, Client, Transport)
├── Building an MCP server
└── Hands-on: Custom MCP tool server
```

---

## 🔷 CHAPTER 10: Production & Interview Preparation

### Module 01: LLMOps & Deployment
```
Topics:
├── LangSmith: Tracing, evaluation, monitoring
├── Caching strategies (semantic caching)
├── Cost optimization
├── Streaming responses
├── Deployment options (API, Streamlit, FastAPI)
└── Hands-on: Deploy an agent with monitoring
```

### Module 02: Guardrails & Safety
```
Topics:
├── Prompt injection attacks (and defense)
├── Input validation & output filtering
├── PII detection and redaction
├── Content moderation
├── Ethical AI considerations
└── Hands-on: Build guardrails for a chatbot
```

### Module 03: Interview Mastery
```
Topics:
├── 50+ Interview Q&A (with expert answers)
│   ├── LLM Fundamentals (10 questions)
│   ├── RAG (10 questions)
│   ├── Agents & Orchestration (10 questions)
│   ├── System Design (10 questions)
│   └── Production & Safety (10 questions)
├── System Design: "Design a RAG-based customer support bot"
├── System Design: "Design a multi-agent code review system"
├── Take-home project walkthrough
└── Behavioral + technical strategy
```

---

## 🎓 CAPSTONE PROJECTS

### Project 1: RAG Knowledge Assistant
```
Build a full RAG system that:
- Ingests company documents (PDF, DOCX, web)
- Answers questions with citations
- Handles follow-up questions
- Evaluates answer quality
```

### Project 2: Multi-Agent Researcher
```
Build a multi-agent system that:
- Takes a research topic
- Agent 1: Searches the web
- Agent 2: Analyzes and summarizes
- Agent 3: Writes a report
- Supervisor coordinates the workflow
```

### Project 3: GenAI SaaS Backend
```
Build a production-ready backend with:
- FastAPI endpoints
- LangGraph agent with tools
- Database integration
- LangSmith monitoring
- Guardrails and rate limiting
```

---

## 📊 Interview Topic Coverage Matrix

| Topic | Chapter | Frequency in Interviews |
|-------|---------|----------------------|
| LLM Architecture / Transformers | Ch 01 | ⭐⭐⭐⭐⭐ |
| Prompt Engineering | Ch 02 | ⭐⭐⭐⭐ |
| LangChain / Frameworks | Ch 03 | ⭐⭐⭐⭐⭐ |
| Embeddings & Vector DBs | Ch 04 | ⭐⭐⭐⭐⭐ |
| RAG (basic + advanced) | Ch 05 | ⭐⭐⭐⭐⭐ |
| AI Agents | Ch 06 | ⭐⭐⭐⭐⭐ |
| LangGraph | Ch 07 | ⭐⭐⭐⭐ |
| Multi-Agent Systems | Ch 08 | ⭐⭐⭐ |
| Fine-Tuning | Ch 09 | ⭐⭐⭐ |
| MCP Protocol | Ch 09 | ⭐⭐ |
| LLMOps / Production | Ch 10 | ⭐⭐⭐⭐ |
| Safety / Guardrails | Ch 10 | ⭐⭐⭐⭐ |
| System Design | Ch 10 | ⭐⭐⭐⭐⭐ |

---

## ⚡ Quick Learning Path Options

### 🏃 Sprint (7-10 days) — "Interview in 2 weeks"
Ch01 (1 day) → Ch02 (1 day) → Ch03 (1 day) → Ch04 (0.5 day) → Ch05 (2 days) → Ch06 (1 day) → Ch07 (1.5 days) → Ch10.Module03 (1 day)

### 🚶 Standard (3-4 weeks) — "Full preparation"
All chapters in order, 2-3 hours/day

### 🧘 Deep Dive (6-8 weeks) — "Mastery + portfolio"
All chapters + all 3 capstone projects + blog posts

---

> **Latest Stack Versions (April 2026):**
> - LangChain: 1.2.15
> - LangGraph: 1.1.x
> - Python: 3.11+
> - OpenAI: GPT-4o, GPT-4.1
> - Anthropic: Claude 4 Opus/Sonnet
> - Google: Gemini 2.5 Pro/Flash
