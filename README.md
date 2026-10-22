<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:0d7377,100:14ffec&height=200&section=header&text=Rounak%20Topdar&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Senior%20GenAI%20Engineer%20%E2%80%A2%20Multi-Agent%20Systems%20Architect&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="Rounak Topdar — Senior GenAI Engineer"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=14FFEC&center=true&vCenter=true&width=720&lines=Building+production-grade+multi-agent+LLM+systems;Agentic+workflows+%E2%80%A2+RAG+%E2%80%A2+Harness+engineering;LLM-as-a-judge+evals+%2B+end-to-end+observability;Shipping+enterprise+GenAI+on+Azure+%E2%98%81%EF%B8%8F" alt="Typing SVG"/>
</a>

<br/>

<a href="https://www.linkedin.com/in/rtopdar/"><img src="https://img.shields.io/badge/LinkedIn-rtopdar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:rounak2002topdar@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hi-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://drive.google.com/file/d/1aMOiGoRoqfUSAqyrJSJx40F25zu3V60O/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-View-14FFEC?style=for-the-badge&logo=googledrive&logoColor=black" alt="Resume"/></a>
<img src="https://komarev.com/ghpvc/?username=RTopdar&style=for-the-badge&color=0d7377&label=PROFILE+VIEWS" alt="Profile views"/>

</div>

---

## 🧠 About Me

```python
class RounakTopdar:
    role       = "Senior GenAI Engineer @ EY GDS (AI & Data Consultant)"
    based_in   = "Kolkata, India 🇮🇳"
    experience = "3+ years shipping production-grade agentic AI"
    domains    = ["Media Compliance", "Banking", "Risk Consulting", "Customer Support"]

    focus = {
        "agentic_ai":    ["Multi-agent orchestration", "MCP", "A2A", "Harness engineering"],
        "retrieval":     ["RAG over SQL/NoSQL vector stores", "Vectorless RAG", "LLM-Wiki / OKF"],
        "reliability":   ["LLM-as-a-judge evals", "Langfuse", "Guardrails", "HITL review gates"],
        "cloud":         ["Azure Container Apps", "Durable Functions", "App Insights", "CI/CD"],
    }

    def philosophy(self):
        return "No black boxes. Every agent instrumented, evaluated and shipped."
```

I turn ambiguous business problems into **deployed, measurable GenAI systems** — from architecture and agent design to evaluation pipelines and cloud rollout.

---

## 🚀 Flagship Work

<details open>
<summary><b>🏗️ Full-Scale PDLC Orchestration Platform</b> — GitHub Copilot CLI SDK + Claude Agent SDK</summary>
<br/>

An end-to-end **Product Development Lifecycle** platform where PMs, architects and developers collaborate through *markdown-as-source-of-truth* documents — driven by a dual AI orchestration layer.

```mermaid
flowchart LR
    U([👤 PM / Architect / Dev]) --> O{{Orchestration Layer<br/>Copilot CLI SDK ⇄ Claude Agent SDK}}
    O --> S1[Intent Gathering] --> S2[BRD / TRD] --> S3[HLD / LLD] --> S4[Work Items]
    S4 -->|HITL review gate| K[(Jira / Azure Boards / Slack)]
    O -.lifecycle hooks.-> E[🧪 LLM-as-a-Judge<br/>Eval Engine]
    O -.-> W[(📚 LLM-Wiki KB<br/>Google OKF + Agent Skills)]
```

- 🔒 **Secure, isolated agent instances** per team/session with strict tenant & data isolation
- 🧪 Custom **eval engines** on lifecycle event hooks — tool-call monitoring + LLM-as-a-judge at every stage
- ✋ **Human-in-the-loop gates** before docs become tracked work items
- ⚡ LLM-wiki knowledgebase cut incident resolution to **3–10 min** for L1/L2/L3 engineers

</details>

<details>
<summary><b>🎙️ No-Code Voice Multi-Agent Platform</b> — Enterprise Customer Support</summary>
<br/>

- Context-aware voice agents (OpenAI Agents SDK + Realtime API) across **retail, e-commerce & healthcare**, with **Twilio IVR** and HITL escalation on low confidence
- Multi-layered memory: in-session, cross-session summary, per-user long-term
- Observability via **App Insights + structlog + Langfuse**, sentiment analysis, **Temporal**-orchestrated summarisation
- PII redaction, harmful-content filtering, output verification; per-user **token budgets with circuit breakers**
- Stateless backend on **Azure Container Apps** with session affinity & horizontal autoscaling

</details>

<details>
<summary><b>🧩 No-Code Agentic Workflow Builder</b> — Enterprise Departments</summary>
<br/>

- Cross-department multi-agent workflows on **Microsoft Agent Framework**, model-agnostic (incl. local / fine-tuned LLMs)
- **MCP servers + A2A** interop with per-department isolated vector DBs
- Smart orchestrator handoff for sub-agent delegation; operator HITL portal
- Three-portal architecture (admin / operator / end-user) on microservices with automated failover

</details>

<details>
<summary><b>📄 Marketing Compliance Document Processing</b></summary>
<br/>

- Re-architected a monolith into **microservices** for independent deployment & targeted scaling
- Document processor as an **MCP client** to compliance tooling servers; long-running pipelines on **Azure Durable Functions** with **SSE** progress streaming

</details>

---

## 🛠️ Tech Stack

<div align="center">

**🤖 Agentic AI & LLM Frameworks**

<img src="https://img.shields.io/badge/OpenAI_Agents_SDK-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude_Agent_SDK-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Copilot_CLI_SDK-181717?style=flat-square&logo=githubcopilot&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/MS_Agent_Framework-5E5E5E?style=flat-square&logo=microsoft&logoColor=white"/>
<img src="https://img.shields.io/badge/Google_ADK-4285F4?style=flat-square&logo=google&logoColor=white"/>
<img src="https://img.shields.io/badge/Azure_AI_Foundry-0078D4?style=flat-square&logo=microsoftazure&logoColor=white"/>

**🔌 Protocols · Context · Evals**

<img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=modelcontextprotocol&logoColor=white"/>
<img src="https://img.shields.io/badge/A2A-0d7377?style=flat-square"/>
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white"/>
<img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat-square&logo=langfuse&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/Temporal-000000?style=flat-square&logo=temporal&logoColor=white"/>

**⚙️ Languages · Backend · Frontend**

<img src="https://skillicons.dev/icons?i=python,js,ts,fastapi,flask,nodejs,express,react,nextjs&perline=9" alt="languages and frameworks"/>

**☁️ Cloud · Data · DevOps**

<img src="https://skillicons.dev/icons?i=azure,gcp,aws,docker,mongodb,firebase,git,githubactions,linux&perline=9" alt="cloud and devops"/>

**🧑‍💻 Coding Agents I work with daily**

<img src="https://img.shields.io/badge/Claude_Code-D97757?style=flat-square&logo=anthropic&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Copilot_CLI-181717?style=flat-square&logo=githubcopilot&logoColor=white"/>
<img src="https://img.shields.io/badge/Codex-412991?style=flat-square&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Cursor-000000?style=flat-square&logo=cursor&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCode-333333?style=flat-square"/>

</div>

---

## 💼 Experience

| 🏢 Company | 🎯 Role | 📅 Period |
|---|---|---|
| **EY Global Delivery Services LLP** | AI & Data Consultant, Technology Consulting — leading GenAI platform builds | Feb 2025 – Present |
| **AlphaDnA / Gnosis Lab** | Associate Software Developer · Full Stack Application Consultant | Aug 2023 – Feb 2025 |

<details>
<summary><b>Highlights from AlphaDnA / Gnosis Lab</b></summary>
<br/>

- 📈 Asset-visualization platform (MongoDB + Express.js) → **+20% decision speed**, **−50% API response time**
- 🔐 Okta OIDC auth with multi-level access control + audit logging
- ☁️ GCP deployment pipelines and a **zero-disruption migration to AWS**
- 🛍️ React product catalog with Python REST APIs + **Milvus** embedding-based recommendations
- 📄 Legal document translation platform on Firebase with Google SSO passwordless auth

</details>

---

## 🏅 Certifications

<div align="center">

| Certification | Issuer |
|---|---|
| 🤖 Azure AI Apps and Agents Developer Associate (**AI-103**) | Microsoft |
| 🧠 Azure Agentic AI Fundamentals (**AI-901**) | Microsoft |
| ⚡ [Azure Developer Associate (**AZ-204**)](https://learn.microsoft.com/api/credentials/share/en-gb/RounakTopdar-6363/7DBFE9C5F4EF9C5E?sharingId=A172CAF2E331B36) | Microsoft |
| ☁️ [Azure Fundamentals (**AZ-900**)](https://learn.microsoft.com/api/credentials/share/en-gb/RounakTopdar-6363/4DDD2701CE52B57B?sharingId=A172CAF2E331B36) | Microsoft |
| 🧱 Databricks Certified Generative AI Engineer Associate | Databricks |
| 🐙 [GitHub Copilot (**GH-300**)](https://learn.microsoft.com/api/credentials/share/en-gb/RounakTopdar-6363/638C6B0EBDB6FBBF?sharingId=A172CAF2E331B36) | GitHub |
| 🌱 [GitHub Foundations (**GH-900**)](https://learn.microsoft.com/api/credentials/share/en-gb/RounakTopdar-6363/34BA532001B2617C?sharingId=A172CAF2E331B36) | GitHub |
| 📮 30 Days of Postman | Postman |

🎓 **B.Tech, Computer Science & Engineering** — University of Engineering and Management, Kolkata (2019–2023) · GPA 8.36 / 10

</div>

---

## 📊 GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=RTopdar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&hide_rank=true&hide=contribs" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RTopdar&layout=compact&theme=tokyonight&hide_border=true&langs_count=6&hide=html,css,scss,jupyter%20notebook" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=RTopdar&theme=tokyonight&hide_border=true" alt="GitHub streak"/>



</div>

---

## 🌱 Currently Exploring

- 🔍 Advanced RAG — hybrid search, query routing, dynamic context windows
- 🧬 Domain fine-tuning with LoRA / QLoRA
- 🛡️ LLM security — prompt-injection defence & jailbreak detection
- 📡 Real-time AI monitoring at enterprise scale
- 🇩🇪 German — working toward B2

---

## 🐍 Contribution Snake

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RTopdar/RTopdar/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RTopdar/RTopdar/output/github-contribution-grid-snake.svg"/>
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/RTopdar/RTopdar/output/github-contribution-grid-snake.svg"/>
</picture>
</div>

---

<div align="center">

### 🤝 Let's build production-grade GenAI together

<a href="https://www.linkedin.com/in/rtopdar/"><img src="https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:rounak2002topdar@gmail.com"><img src="https://img.shields.io/badge/Drop_a-Mail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<sub>⚡ Always learning, always shipping ⚡</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:14ffec,50:0d7377,100:0f2027&height=110&section=footer" width="100%"/>

</div>
