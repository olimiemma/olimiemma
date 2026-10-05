<h1 align="center">Emmanuel Olimi Kasigazi</h1>
<p align="center"><b>Data & LLM Engineer</b> · New York</p>
<p align="center">I build data pipelines and AI applications, from stakeholder requirements to delivery.</p>
<p align="center">
  <a href="https://www.olimiemma.com/">Website</a>·
  <a href="https://www.linkedin.com/in/olimiemma/">LinkedIn</a> ·
  <a href="https://medium.com/@olimiemma">Medium</a> ·
  <a href="https://huggingface.co/olimiemma">Hugging Face</a> ·
  <a href="https://public.tableau.com/app/profile/emmanuel.kasigazi/">Tableau</a> ·
  <a href="https://calendly.com/olimiemma">Book a call</a>
</p>

---
I’m a New York–based Data & LLM Engineer who builds data pipelines and AI applications, taking projects from stakeholder requirements through implementation and delivery. My background in software development, business leadership, and communications helps me translate business needs into technical solutions, explain tradeoffs, and support the people who use them. I hold an M.S. in Data Analytics and Visualization from Yeshiva University in Manhattan, NY and a MicroMasters in Statistics and Data Science from the Massachusetts Institute of Technology.

Everyone wants AI. AI runs on good data. I work both halves: **finding the data that is missing, fixing the data that exists, building the pipelines that keep it reliable, and putting AI applications on top**, then staying through delivery so the people using it actually adopt it.

14+ years across tech, government, health, media, non-profits and education · National Science Foundation I-Corps Fellow · VC Lab-certified Venture Institute Fellow.

## What I do

**Data engineering.** Production ETL and ELT, batch and stream processing, orchestration (Airflow), dimensional modeling (star schema, SCD2), and the data-quality work that makes any of it trustworthy. I have consolidated 100+ fragmented sources into one master database at 99%+ integrity and processed 300M+ records at scale. Python, SQL, Snowflake (streams, tasks, dynamic tables), PostgreSQL, Databricks (Delta Lake, Unity Catalog), Microsoft Fabric.

**LLM and agentic AI.** Production RAG from ingestion to eval: hybrid retrieval, BGE-M3 and OpenAI embeddings, ChromaDB and vector search, multi-model routing (LiteLLM), agentic orchestration (LangGraph, custom multi-agent), and MCP server design. I ship with evaluation harnesses, not vibes: LLM-as-judge, RAGAS, Mean Reciprocal Rank 0.990 and Precision@3 0.993 on AXAM. I also do the hard part most people skip, quantized on-device inference that runs fully offline on zero-GPU hardware (llama.cpp, GGUF, Ollama), including a three-tier serving layer that cut latency from 285s to 18.9s.

**Analytics and data science.** Statistics, explainable ML, and dashboards people actually open on a Monday. Real-world stakes, from ICU survival prediction to household financial risk, communicated so a decision-maker can act. Python, R, Tableau, Power BI, scikit-learn, SHAP.

**Leadership and communication.** I translate business needs into technical plans and then move the room. 200+ National Science Foundation customer-discovery interviews, teams of 7 to 20+, VC Lab-certified in deal diligence and fund modeling, and an MIT OpenCourseWare podcast that reached 6M+ people. Stakeholder discovery, requirements, public speaking, brand and design.

## Selected work

**New York, at scale:** two end-to-end pipelines over the city's public record.
- [NYC 311 noise analytics](https://github.com/olimiemma/New-York-City-Noise-NOISE-COMPLAINTS-ANALYSIS): 300M+ records mapped to borough, street and zip-code hotspots ([write-up](https://medium.com/@olimiemma/data-speaks-understanding-new-york-citys-noise-landscape-apodcast-c93d7bcf419b))
- [25 years of NYT headlines](https://github.com/olimiemma/NYT-analysis-2K-2K5): 2.2M headlines through TF-IDF era analysis, VADER sentiment, spaCy NER, and a fully local RAG chatbot ([write-up](https://medium.com/@olimiemma/i-analyzed-2-2-0718f706c3bb))

**Data quality engine:** consolidated fragmented alumni sources (20,918 messy rows) into 5,556 verified records at 99%+ integrity, plus a RAG chatbot so non-technical staff can query it in plain English.

**[BiZaas](https://bizaas.olimiemma.workers.dev/):** enterprise AI command center. Work Memory turns staff expertise into permissioned knowledge objects; a copilot answers from company data with citations; multi-model routing, human approval inbox, and admin governance.

**[KalshiBots](https://kalshibots.net)**: production marketplace with 15 algorithmic trading systems for prediction markets (dual-loop agent, UCB bandit strategy selection) (dual-loop architecture, UCB bandits, 13 strategy variants). Related: a [hybrid neuro-symbolic ARC-AGI-2 solver](https://github.com/olimiemma/ARC-Prize-2025-Kaggle-ARC-AGI-2-Benchmark-).

**[AXAM](https://axamai.org):** offline-first AI learning platform running 7,617 MIT OpenCourseWare lectures (121K+ vectors) on classroom machines with no internet and no GPU. Outstanding Impact in Science & Technology, Katz School Symposium. ([repo](https://github.com/olimiemma/AXAM-Voice-Q-A-System) · [dataset](https://huggingface.co/datasets/olimiemma/MIT-OCW-Transcripts))

**[Laba Party](https://labapartymain.pages.dev/):** offline-first PWA party game, cultural card game app, ~31K monthly users in 54 countries, 11M+ cards played
.

**Also:** [NASA Space MCP server](https://github.com/olimiemma/NASA-SPACE-MCP-SERVER-COMPLETE-) (agentic tool use) · [ICU survival prediction](https://github.com/olimiemma/ICU-Survival-Prediction-Using-Logistic-Regression) (interpretable clinical ML) · [TB data warehouse](https://github.com/olimiemma/TB-Data-Warehouse-Type-2-SCD-Implementation) (SCD2 modeling) · [all 69 projects](https://olimiemma.com/projects.html)

## Toolbox

**Languages:** Python (Pandas, FastAPI, async), SQL, R, Java, JavaScript/TypeScript, Bash

**Data engineering:** ETL/ELT pipelines, batch and stream processing, orchestration (Airflow), dimensional modeling, schema design, normalization, indexing, ACID, OLTP vs OLAP, materialized views, stored procedures, data quality and governance

**Databases and platforms:** CloudFlare, AWS, Azure, Snowflake (streams, tasks, dynamic tables), PostgreSQL, MySQL, Oracle, MongoDB, Databricks (Delta Lake, Unity Catalog, Model Serving), Microsoft Fabric, ChromaDB

**AI, LLM and agentic:** RAG, hybrid retrieval, embeddings (BGE-M3, OpenAI), vector search, multi-provider integration (OpenAI, Anthropic, Gemini, DeepSeek, Grok) via OpenRouter, Groq and OpenAI-compatible endpoints, multi-model routing (LiteLLM), framework selection (LangChain, LlamaIndex), agentic orchestration (LangGraph, OpenAI Agents SDK, custom multi-agent), MCP servers, tool/function calling with structured JSON, prompt and context engineering, tokenization (tiktoken, BPE), on-device/offline inference and quantization (llama.cpp, GGUF, Ollama), fine-tuning (QLoRA, LoRA, PEFT) and data curation, prompt-injection defense

**LLM evaluation and ops:** LLM-as-judge, RAGAS, Mean Reciprocal Rank and Precision@k, observability (Weights & Biases, Langfuse, MLflow), serverless GPU deployment (Modal), app UIs and hosting (Gradio, Hugging Face Spaces), Hugging Face, PyTorch, OpenAI/Anthropic SDKs

**Analytics and BI:** statistics, explainable ML (scikit-learn, SHAP), Tableau, Power BI, Microsoft Fabric

**Cloud and infra:** AWS, Azure (Azure OpenAI, ADLS Gen2, Entra ID, Key Vault), Cloudflare (Workers, Pages, R2), Docker, Kubernetes, CI/CD, Git, Linux (daily driver, 16+ years)

**AI-assisted development:** Claude Code, Codex, Mistral(vibe), GeminiCLI, Cursor, AntiGravity

## Recognition

• National Science Foundation I-Corps Fellow | 2025: Selected for the federal government's flagship commercialization
program
• Podcast co-host for MIT OpenCourseWare; featured in the documentary [The Courage to Be Open](https://youtu.be/RkhSkE89KJ0?t=446)
• President, Katz African Students Association, Yeshiva University | 2025-26: Led a 7-member executive team serving 1,700+
STEM graduate students
• Winner, Resilient Africa Network Innovation Grant | 2016: E-musawo telemedicine platform
• Selected Presenter, OEGlobal 2026 Conference | Massachusetts Institute of Technology, Cambridge, MA
• Selected Presenter, State University of New York AI Industry Showcase | Stony Brook University, 2026: showcased AXAM's
offline retrieval-augmented generation system
• Outstanding Impact in Science and Technology Award | Yeshiva University Katz School Symposium on Science, Technology
and Health, 2026: for AXAM
