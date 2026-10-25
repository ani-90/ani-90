<h1 align="center">Anirudh Balakrishnan</h1>

<p align="center">
  <b>Software Engineer @ Caterpillar · Machine Learning and Data Engineering</b><br>
  Building AI agents that are deterministic, verifiable and safe to run on real systems.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/anirudh-balakrishnan-5700041a7/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:anirudhbala13@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

---

## 👋 About me

I'm a software engineer at **Caterpillar Inc.** in Bengaluru, working on Machine Learning and Data Engineering. Outside work I build **agentic AI systems and developer tooling**, and I care most about one question: *how do you make an AI agent reliable enough to trust?*

My answer so far: let the LLM do the discovery and reasoning once, then **compile the result into deterministic, typed, auditable code**. Cite every claim to evidence, and never let a system guess when it can verify.

## 🔭 What I'm focused on

- 🤖 **Reliable agents:** moving LLM agents from "works in a demo" to repeatable, auditable behaviour
- 🧰 **Tools for AI coding assistants:** MCP servers that give assistants accurate context
- 📊 **Applied ML:** anomaly detection on telematics data.
---

## 🚀 Featured projects

### ⚙️ [Capability Compiler](https://github.com/ani-90/Computer-Use-Automation-System): deterministic agentic computer use
An LLM agent (ReAct + Playwright) discovers multi-step banking workflows from a goal alone, then **compiles them into typed, versioned, parameterized capabilities**. After discovery, runs use a **zero-LLM replay engine**: seconds per run at no inference cost.

- 🛡️ Safety controls for irreversible financial actions: a retry contract, a never-re-click-after-dispatch invariant, policy gates enforced in code, and live human takeover for high-value approvals
- 🧪 Business / recoverable / hard failure taxonomy, validated across **23+ replay runs** with injected faults
- 🔌 Automations exposed as callable tools over an API, so outside agents can discover and invoke them with typed inputs and outputs

`Python` `Playwright` `Pydantic` `LLMs (ReAct)` `pytest`

### 🗺️ [RudhMap](https://github.com/ani-90/RudhMap): an MCP server that maps how a codebase is wired
Gives AI coding assistants (like Claude Code) an accurate map of a repo. **Tree-sitter** traces function calls across Python, TypeScript and infrastructure files, **cites every call to its exact file and line**, and discards any citation that doesn't exist on disk.

- 🔗 Import-aware cross-file call tracing that links a call only when exactly one function matches, so the map never guesses: resolved connections went from **47 → 81** on a real FastAPI codebase
- 🧪 **244 automated tests**
- 📉 Benchmarked head-to-head with Claude Code on 8 questions across 2 repos: **39% fewer agent steps** (28 → 17 turns)

`Python` `MCP` `tree-sitter` `NetworkX`

### 📰 [AI-Powered News Learning App](https://github.com/ani-90/Knowledge-News-App)
A full-stack Android app (**Flutter + FastAPI**, deployed on Railway) that serves news across 7 knowledge domains.

- 🧠 A **LangGraph** pipeline runs 7 domain agents in parallel, with LLM-generated queries pulling from Tavily and NewsAPI, and stays within rate limits using a shared concurrency limit and exponential backoff
- 🎓 Active-learning features: LLM-generated quizzes graded on the server, a multi-turn AI debate mode, and per-domain quiz tracking

`Flutter` `LangGraph` `FastAPI` `Llama 3.3 70B (Groq)` `PostgreSQL`

### 📈 [Stock Market Time Series Research](https://github.com/ani-90/Combining-Time-Series-Models)
Ensembled ARIMA/ARMA forecasts for BSE Bankex and Auto stocks: clustered correlated stocks (PCA, hierarchical clustering), fit AIC-selected models per cluster, and optimized convex ensemble weights to minimize MSE on held-out prices.

`Python` `statsmodels` `SciPy`

---

## 🛠️ Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Agentic AI:** LangGraph · MCP · ReAct agents · deterministic replay · Pydantic · pytest
**ML & data:** HDBSCAN · XGBoost · anomaly detection · Snowflake · AWS Lambda / Step Functions

## 🏆 Highlights

- 🥇 Winner, **CAT DIGITAL India Early Talent Hackathon** (July 2025)
- ☁️ **AWS Certified Cloud Practitioner** (CLF-C02)
- 🎓 M.Sc. Software Systems, PSG College of Technology · Diploma in Programming & Data Science, IIT Madras

## 📫 Let's connect

Open to talking about agentic AI, MCP tooling and applied ML.
[LinkedIn](https://www.linkedin.com/in/anirudh-balakrishnan-5700041a7/) · [Email](mailto:anirudhbala13@gmail.com)
