# AI Forward Deployed Engineer (FDE) Bootcamp — Learning Tracker & Workspace

[![Course Provider](https://img.shields.io/badge/Udemy-Course-EC5252?style=for-the-badge&logo=udemy&logoColor=white)](https://www.udemy.com/course/ai-forward-deployed-engineer-fde-bootcamp/)
[![Instructor](https://img.shields.io/badge/Instructor-Krish%20Naik%20%7C%20KRISHAI-0A66C2?style=for-the-badge)](https://www.udemy.com/user/krish-c-naik/)
[![Course Duration](https://img.shields.io/badge/Duration-36h%2035m-brightgreen?style=for-the-badge)](https://www.udemy.com/course/ai-forward-deployed-engineer-fde-bootcamp/)
[![Curriculum](https://img.shields.io/badge/Curriculum-33%20Sections%20%E2%80%A2%20175%20Lectures-blue?style=for-the-badge)](https://www.udemy.com/course/ai-forward-deployed-engineer-fde-bootcamp/)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![GCP](https://img.shields.io/badge/Google%20Cloud-Platform-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://cloud.google.com)

> **GitHub Repository Description (< 300 chars):**  
> *Course notes, enterprise GenAI projects, and hands-on implementations from the AI Forward Deployed Engineer (FDE) Bootcamp on Udemy. Covers Agentic AI, LangGraph, Enterprise RAG, MCP, API integrations, and production deployment.*

---

## 📌 About The Forward Deployed Engineer (FDE) Role

The **Forward Deployed Engineer (FDE)** role—originally pioneered by **Palantir**—is one of the most critical and strategic roles in the Generative AI era. While traditional Software Engineers build core products and Data Scientists experiment with offline models, an **AI FDE** deploys directly to the front line with enterprise clients.

An AI FDE operates at the cross-section of:
1. **Applied AI & Agentic Engineering:** Building robust agents, decision systems, multi-modal pipelines, and RAG architectures.
2. **Enterprise Integration:** Plumbing modern AI into messy legacy architectures (Hospital Management Systems, custom ERPs, internal mail servers, legacy SQL/NoSQL databases).
3. **Strategic Client Leadership:** Leading discovery sessions, writing Statement of Work (SOW) documents, defending against scope creep, briefing senior leadership/C-suite under incident pressure, and ensuring governance/security compliance.

```
┌────────────────────────────────────────────────────────────────────────┐
│                   The Forward Deployed Engineer (FDE)                  │
├─────────────────────┬──────────────────────────┬───────────────────────┤
│  Applied AI Tech    │   Enterprise Systems     │ Strategic Leadership  │
├─────────────────────┼──────────────────────────┼───────────────────────┤
│ • Pydantic AI       │ • Google Cloud (GCP)     │ • Discovery Workshops │
│ • Google ADK        │ • Docker & Cloud Run     │ • SOW Scoping         │
│ • Jev Decision Mod. │ • MongoDB & SQL Data     │ • C-Suite / VP Briefs │
│ • NeMo Guardrails   │ • Legacy ERPs & HMS      │ • Incident Response   │
│ • Bifrost Gateways  │ • Observability (Logfire)│ • UAT Runbooks        │
│ • Qdrant Vector RAG │ • DeepEval & RAGAS Evals │ • Security Reviews    │
└─────────────────────┴──────────────────────────┴───────────────────────┘
```

---

## 📂 Recommended Repository Structure

This repository is organized to match the hands-on progression of the bootcamp:

```text
My_FDE/
│
├── README.md                                  # Course syllabus & personal progress tracker
├── docs/
│   ├── discovery-playbooks/                   # SOW templates, discovery questionnaires, UAT runbooks
│   ├── architecture-diagrams/                 # System designs, sequence diagrams, FDE process maps
│   └── governance-and-security/               # Threat models, CISO review checklists, red-team reports
│
├── 01-fde-fundamentals/                       # Discovery notes, real job specs analysis, client briefs
├── 02-gcp-cloud-foundations/                  # IAM configs, gcloud scripts, billing optimization, spot VM setups
├── 03-pydantic-ai-agents/                     # Single agent, structured JSON models, RunContext, custom tools
├── 04-observability-and-guardrails/           # Pydantic Logfire traces, NeMo Guardrails, red-teaming scripts
├── 05-llm-gateways-and-rag/                   # Bifrost configurations, MCP gateway, Qdrant vector store
├── 06-google-adk-workflows/                   # Multi-modal agents (Image/Audio/Video), dynamic routing
├── 07-jev-decision-models/                    # Jev TypeSafe routing, emergency triage, Vertex AI workflows
├── 08-evaluations-and-benchmarking/           # RAGAS metrics, DeepEval implementations, LLM-as-a-judge
│
└── projects/
    ├── 01-claimtrail-hospital-hms/            # Hospital insurance letter parsing, reconciliation tab, HMS connectors
    ├── 02-nemo-secure-hr-bot/                 # Secure enterprise HR assistant, input/output rail tests
    ├── 03-bifrost-qdrant-enterprise-rag/      # Multi-provider LLM gateway, virtual keys, Qdrant retrieval
    ├── 04-flood-sos-emergency-triage/         # Google ADK + Jev government emergency response system
    ├── 05-ecommerce-cto-poc/                  # MongoDB, Docker containerization, Cloud Run, CTO pitch & report
    └── 06-crossexam-doc-intelligence/         # Real-world distributor logistics & banking scenario
```

---

## 🏆 Featured Portfolio Projects

| Project | Core Stack | Client Problem & Deliverable |
|---|---|---|
| **ClaimTrail (Nirmaya Hospital)** | Pydantic AI, Gemini, HMS, PDF parsing | Automated reconciliation of manual insurer settlement letters with hospital billing databases. Reconciled 30/30 claims automatically. |
| **Secure Enterprise HR Chatbot** | NeMo Guardrails, Python, LLM Security | Production HR bot resilient against prompt injections, jailbreaks, and sensitive data leakage. Includes CISO review documentation. |
| **Bifrost Gateway & Qdrant RAG** | Bifrost, Qdrant Cloud, MCP Virtual Keys | Enterprise RAG system featuring automated multi-provider fallbacks, latency/cost telemetry, and secure virtual keys. |
| **Flood SOS Emergency Triage** | Google ADK, Jev Decision Model, Vertex AI | High-speed decision and dynamic routing layer for emergency rescue helplines and triage automation. |
| **E-Commerce Enterprise POC** | MongoDB, Docker, GCP Cloud Run, FastAPI | Complete FDE lifecycle: CTO proposal, legacy inventory integration, agent security, Dockerized deployment, and technical reports. |
| **CrossExam Document Intelligence** | Multi-Agent Architecture, Document AI | Logistics shipment processing and multi-party document validation in complex, regulated enterprise environments. |

---

## 📋 Complete Syllabus & Progress Tracker

Track your progress through all **33 sections** and **175 lectures** (36h 35m). Check off items (`- [x]`) as you complete them.

### Module 1: The FDE Mindset & Client Discovery Playbook

#### Section 1: Introduction & Who is a Forward Deployed Engineer
- [ ] `01` Introduction *(2:11)*
- [ ] `02` Course Resources + Tracker *(0:06)*
- [ ] `03` Who is a Forward Deployed Engineer *(10:02)*
- [ ] `04` Where the job came from *(10:05)*
- [ ] `05` Why this job, and why now *(9:34)*
- [ ] `06` Important Initiative For everyone *(3:48)*
- [ ] `07` Who hires FDEs *(6:05)*
- [ ] `08` Reading real job descriptions *(11:07)*
- [ ] `09` What FDEs actually do *(5:23)*

#### Section 2: Client Discovery & Requirements Gathering
- [ ] `10` Understanding a client's real need *(8:13)*
- [ ] `11` Asking good questions *(10:11)*
- [ ] `12` **[Role-Play Exercise]** Discovery Call: Find the Real Problem

#### Section 3: The Engagement Lifecycle & Scoping (SOW)
- [ ] `13` The real engagement lifecycle *(8:51)*
- [ ] `14` Running a domain discovery workshop *(14:21)*
- [ ] `15` Data classification *(11:42)*
- [ ] `16` Where human-in-the-loop belongs *(12:51)*
- [ ] `17` Writing the scope document and SOW *(11:30)*
- [ ] `18` **[Role-Play Exercise]** Scope Creep: Protect the SOW
- [ ] `19` Test environments and the UAT runbook *(10:56)*
- [ ] `20` When the client's tooling isn't what you expected *(10:12)*
- [ ] `21` **[Deliverable Assignment]** Write a 1-Page Scope Document (SOW) for a Real Client Brief

#### Section 4: FDE Playbook: Stakeholder Communication & Crisis Management
- [ ] `22` FDE Playbook: Discovery to Delivery (Overview)
- [ ] `23` Translating technical work into business value *(11:45)*
- [ ] `24` Answer first: structuring for senior stakeholders *(9:46)*
- [ ] `25` Answering under pressure *(9:21)*
- [ ] `26` **[Role-Play Exercise]** Production Incident: Brief an Angry VP
- [ ] `27` Adapting to who is listening: Stakeholder management styles *(10:27)*

---

### Module 2: Cloud Infrastructure & Google Cloud Foundations

#### Section 5: Google Cloud Fundamentals for FDEs
- [ ] `28` Why Cloud Skills Matter for Forward Deployed Engineers (FDE) *(8:24)*
- [ ] `29` What Is Cloud Computing? IaaS, PaaS & SaaS Explained *(13:19)*
- [ ] `30` Create a Google Cloud Free Tier Account (GCP Setup Step-by-Step) *(6:02)*
- [ ] `31` Google Cloud Console Tour: Projects, APIs & Key Services *(10:51)*
- [ ] `32` Hands-On: Build & Deploy Your First Google Cloud Project *(22:16)*
- [ ] `33` GCP Billing Explained: Billing Accounts, Budgets & Alerts *(20:47)*
- [ ] `34` Google Cloud IAM: Principals, Roles & Permissions *(17:53)*
- [ ] `35` Create a GCP Service Account & Assign IAM Roles (Hands-On) *(16:51)*
- [ ] `36` GCP Regions & Zones: Choose the Right Location for Latency & Cost *(16:33)*
- [ ] `37` Google Cloud Shell & gcloud CLI: Essential Commands *(10:42)*
- [ ] `38` GCP Cost Optimization: Cut Your Cloud Bill (Spot VMs, Budgets, Labels) *(9:31)*
- [ ] `39` Google Cloud Fundamentals for FDEs (Review)

---

### Module 3: Agentic AI Engineering with Pydantic AI

#### Section 6: LLM Foundations & Agent Frameworks Comparison
- [ ] `40` LLM Providers Explained: OpenAI, Anthropic, Gemini & Open-Source *(15:14)*
- [ ] `41` AI Agent Frameworks Compared: Pydantic AI, Google ADK & LangGraph *(10:20)*
- [ ] `42` Why Pydantic AI now? *(1:33)*

#### Section 7: Pydantic AI Core Concepts & Development
- [ ] `43` Pydantic Ecosystem Overview: Pydantic, Pydantic AI & Logfire *(20:25)*
- [ ] `44` Build Your First Pydantic AI Agent in Python (Hands-On) *(23:31)*
- [ ] `45` Structured Output in Pydantic AI: Return Validated JSON from LLMs *(18:52)*
- [ ] `46` Pydantic Validation for LLM Outputs: Models, Validators & Retries *(15:39)*
- [ ] `47` Dependency Injection in Pydantic AI with RunContext *(15:59)*
- [ ] `48` Tool Calling in Pydantic AI: Give Your Agent Custom Python Tools *(16:23)*
- [ ] `49` Pydantic Logfire: Trace & Monitor AI Agents in Production *(15:25)*
- [ ] `50` Pydantic AI Core Concepts (Summary)

#### Section 8: Mini Projects: Single & Multi-Agent Workflows
- [ ] `51` Mini Project 1: Single AI Agent Use Case & Architecture *(19:34)*
- [ ] `52` Build the Single-Agent Workflow with Pydantic AI *(21:10)*
- [ ] `53` Test & Debug Your AI Agent Workflow *(10:38)*
- [ ] `54` Mini Project 2: Multi-Agent System Use Case & Architecture *(12:30)*
- [ ] `55` Build Multi-Agent Orchestration: Agents Calling Agents *(15:10)*
- [ ] `56` End-to-End Testing with Vibe Coding (AI-Assisted Debugging) *(19:49)*

---

### Module 4: Project ClaimTrail — Enterprise Hospital System Integration

#### Section 9: ClaimTrail: Legacy System Discovery & Setup
- [ ] `57` Project Intro: The Hospital That Retypes Every Insurance Letter *(12:10)*
- [ ] `58` Meet the Legacy System: HMS, Mail Server & Insurers *(22:13)*
- [ ] `59` How the Hospital Works: Claims, Bills & the Database *(9:29)*
- [ ] `60` Setting Up and Running the Legacy System *(15:57)*
- [ ] `61` Inside the HMS: Patients, Claims & Manual Settlements *(11:02)*
- [ ] `62` Inside the Mail Portal: Where Insurer Letters Arrive *(13:55)*
- [ ] `63` The FDE Plan: Where AI Fits (AI Reads, Code Decides) *(15:05)*
- [ ] `64` **[Stakeholder Discovery]** Interview the Hospital Billing Clerk

#### Section 10: ClaimTrail: Pipeline Build, Reconciliation & Delivery
- [ ] `65` From PDF to Structured Data with a Pydantic AI Agent *(19:30)*
- [ ] `66` Connectors: Reading Insurer Mail & HMS Data Safely *(12:53)*
- [ ] `67` Setting Up the LLM: Gemini, Fallbacks & Retries *(18:28)*
- [ ] `68` Business Rules: Matching Claims & Spotting Unfair Cuts *(8:59)*
- [ ] `69` The Agentic Pipeline: Fetch, Read, Match, Decide *(12:35)*
- [ ] `70` Plugging AI into the HMS: The Claim Reconciliation Tab *(11:46)*
- [ ] `71` End-to-End Testing: 30 of 30 Claims Reconciled *(1:34)*
- [ ] `72` Agentic Coding Demo + Your Assignments *(12:29)*
- [ ] `73` **[Hands-On Assignment]** ClaimTrail: Handle Two Real Requests from Nirmaya Hospital

---

### Module 5: Governance, Observability & LLM Security

#### Section 11: AI System Design & Governance Strategy
- [ ] `74` Why AI System Design Matters for FDEs *(15:08)*
- [ ] `75` Why AI Security Matters: Guardrails, Gateways & Evals *(16:33)*
- [ ] `76` What Is AI Governance & Why It Matters *(22:35)*
- [ ] `77` AI Governance Strategy & LLM Security Risks *(13:07)*
- [ ] `78` AI Governance Explained with a Simple Analogy *(21:41)*
- [ ] `79` AI Governance Roadmap for This Course *(0:17)*

#### Section 12: LLM Observability & Tracing with Pydantic Logfire
- [ ] `80` What Is LLM Observability? *(22:57)*
- [ ] `81` Pydantic Logfire Setup & First Trace *(18:39)*
- [ ] `82` LLM Tracing Fundamentals: Traces & Spans *(19:25)*
- [ ] `83` Trace a RAG Pipeline with Logfire *(13:27)*
- [ ] `84` Trace an AI Agent Workflow *(9:53)*
- [ ] `85` Trace a Multi-Agent Workflow *(19:02)*
- [ ] `86` Debug Multi-Agent Workflows with Traces *(10:59)*
- [ ] `87` LLM Observability & Tracing (Review)

#### Section 13: LLM Guardrails & Application Defense
- [ ] `88` What Are LLM Guardrails? *(20:19)*
- [ ] `89` How to Program LLM Guardrails *(12:45)*
- [ ] `90` LLM App Without Guardrails: Prompt Injection Risks *(20:54)*
- [ ] `91` Build Your First LLM Guardrail *(12:18)*
- [ ] `92` Input Guardrails: Block Jailbreaks & Prompt Injection *(17:37)*
- [ ] `93` Custom Guardrails for Business Rules *(16:15)*
- [ ] `94` Output Guardrails: Validate LLM Responses *(14:17)*

#### Section 14: NeMo Guardrails & Enterprise Red-Teaming
- [ ] `95` Build a Secure HR Chatbot with NeMo Guardrails *(14:51)*
- [ ] `96` Jailbreak-Test the HR Chatbot *(15:07)*
- [ ] `97` **[Hands-On Lab]** Red-Team the HR Chatbot
- [ ] `98` **[Role-Play Exercise]** Security Review with the CISO

---

### Module 6: Gateways, RAG & Evaluation Frameworks

#### Section 15: LLM Gateways & Bifrost Architecture
- [ ] `99` What Is an LLM Gateway? *(19:49)*
- [ ] `100` Set Up an LLM Gateway with Multiple Providers *(17:54)*
- [ ] `101` Problems Without an LLM Gateway *(26:34)*
- [ ] `102` First LLM Call Through Bifrost *(13:48)*
- [ ] `103` Bifrost Fallbacks, Streaming & Logging *(14:13)*
- [ ] `104` Bifrost Virtual Keys & MCP Gateway *(22:15)*
- [ ] `105` LLM Gateways & Bifrost (Review)

#### Section 16: Enterprise RAG with Qdrant Cloud
- [ ] `106` RAG Data Ingestion with Qdrant Cloud *(20:58)*
- [ ] `107` RAG Retrieval & Testing via LLM Gateway *(11:26)*

#### Section 17: LLM Evaluation & RAGAS Metrics
- [ ] `108` What Is LLM Evaluation? *(6:59)*
- [ ] `109` LLM Evals Demo: Score Your First App *(0:04)*
- [ ] `110` LLM Evaluation Key Terms Explained *(23:13)*
- [ ] `111` RAGAS Evaluation Metrics Overview *(19:40)*
- [ ] `112` Token Efficiency & LLM Cost Metrics *(20:05)*
- [ ] `113` Faithfulness, Answer Relevancy & Context Precision *(13:29)*
- [ ] `114` Context Recall, Tool Call Accuracy & Answer Correctness *(9:25)*
- [ ] `115` LLM Evaluation & RAGAS Metrics (Review)

---

### Module 7: Google ADK, Jev Decision Models & Flood SOS Capstone

#### Section 18: Google ADK (Agent Development Kit) & Multi-Modal Agents
- [ ] `116` Welcome To Google ADK *(18:28)*
- [ ] `117` Image Generation Agent *(19:46)*
- [ ] `118` Video Generation Agent *(21:51)*
- [ ] `119` Audio Generation Agent *(18:12)*
- [ ] `120` Introduction to the Project *(7:48)*
- [ ] `121` Tools and Callbacks *(8:54)*
- [ ] `122` Agent Deployment on Google Cloud Run *(9:38)*

#### Section 19: Enterprise Automation with Multi-Agent Workflows
- [ ] `123` Enterprise Automation with Multi Agent Workflows *(9:18)*
- [ ] `124` Employee Onboarding multi agent workflow Automation *(20:30)*
- [ ] `125` Dynamic Routing Multi agent workflow *(11:42)*
- [ ] `126` Sub agents vs Root Agents with deployment assignment *(12:36)*

#### Section 20: Decision Models & Jev Fundamentals
- [ ] `127` Jev Explained *(0:03)*
- [ ] `128` Why FDEs Need Decision Models, Not Just LLMs *(14:12)*
- [ ] `129` What Is Jev? How a Decision Model Works *(16:49)*
- [ ] `130` Reading the Jev API Docs the Right Way *(10:17)*
- [ ] `131` Jev Basics: Choice, Score & Noul Questions *(16:43)*
- [ ] `132` Complex Workflow Patterns and Error Handling *(16:27)*

#### Section 21: Jev Practical Use Cases & Vertex AI Integration
- [ ] `133` Jev for Healthcare: Clinical Triage Use Case *(2:56)*
- [ ] `134` WhatsApp business workflow automation with Jev *(9:59)*
- [ ] `135` Jev Limitations: When to Use an LLM Instead *(3:54)*
- [ ] `136` Jev with Google Vertex AI *(14:00)*
- [ ] `137` Jev Decision Model (Review)

#### Section 22: DeepEval & LLM-as-a-Judge Evaluation
- [ ] `138` DeepEval Introduction *(9:39)*
- [ ] `139` LLM Evaluation with a Decision Model *(10:03)*
- [ ] `140` Jev as an LLM-as-a-Judge *(11:06)*
- [ ] `141` Evaluating the Judge: How Reliable Is Jev? *(6:15)*

#### Section 23: Capstone: Flood SOS Emergency Triage (Google ADK + Jev)
- [ ] `142` Government Helpline Desks: The Client Problem *(4:28)*
- [ ] `143` Jev as the Decision Layer for Emergency Triage *(14:54)*
- [ ] `144` Multi-Agent Workflow with Google ADK *(16:57)*
- [ ] `145` Flood SOS App Demo & End-to-End Testing *(4:46)*
- [ ] `146` **[Capstone Assignment]** Scale the Flood SOS App to Production *(2:31)*

---

### Module 8: Full Lifecycle E-Commerce POC (CTO Engagement to Cloud Run)

#### Section 24: E-Commerce Project: Client Onboarding & CTO Pitch
- [ ] `147` Flow of the project and best practices *(8:50)*
- [ ] `148` Project onboarding Meet with CTO *(2:01)*
- [ ] `149` Brainstorming ideas for POC development *(28:41)*
- [ ] `150` Proposal Presentation to CTO for approval *(4:47)*
- [ ] `151` How to create a presentation for client interaction *(8:33)*
- [ ] `152` **[Role-Play Pitch]** Pitch the POC to the CTO
- [ ] `153` Let's stick to the Plan *(1:31)*

#### Section 25: E-Commerce Project: Legacy System Discovery
- [ ] `154` Understanding legacy system assignment *(17:38)*
- [ ] `155` Running the legacy system *(15:56)*
- [ ] `156` Entering POC Development phase *(1:07)*

#### Section 26: E-Commerce Project: MongoDB Setup & Operations
- [ ] `157` Basics of MongoDB *(19:58)*
- [ ] `158` Setting up MongoDB *(14:41)*
- [ ] `159` CRUD operations with MongoDB *(20:59)*

#### Section 27: E-Commerce Project: Agent Development & Security
- [ ] `160` Config Setup for POC development *(16:19)*
- [ ] `161` Designing Helper Functions *(6:50)*
- [ ] `162` Agent Development *(16:21)*
- [ ] `163` Agent Security *(17:50)*
- [ ] `164` Final POC pipeline Test *(22:18)*

#### Section 28: E-Commerce Project: Pre-Integration & Reporting
- [ ] `165` POC Demo Meet *(1:38)*
- [ ] `166` How to design Technical Report before integration *(4:51)*
- [ ] `167` **[Deliverable Assignment]** Write the Pre-Integration Technical Report for the E-commerce POC

#### Section 29: E-Commerce Project: Integration Phase & Evaluations
- [ ] `168` Entering the Integration Phase *(1:00)*
- [ ] `169` Legacy System Integration *(14:30)*
- [ ] `170` Logic for online and Offline Evaluation *(17:18)*
- [ ] `171` Running Evaluations and understanding results *(11:11)*

#### Section 30: E-Commerce Project: Cloud Deployment & Wrap-Up
- [ ] `172` Setting up Google Cloud *(23:28)*
- [ ] `173` Building Docker Image *(19:18)*
- [ ] `174` Integration Deployment on production *(7:54)*
- [ ] `175` Cleanup *(5:04)*
- [ ] `176` HAPPY ENDING *(3:09)*

---

### Module 9: Case Studies: CrossExam & The Real FDE World

#### Section 31: CrossExam: Document Intelligence for a Distributor
- [ ] `177` CrossExam: the whole picture and the FDE role *(12:06)*
- [ ] `178` Meet the client *(9:03)*
- [ ] `179` Month-end in the inbox *(8:20)*
- [ ] `180` The request, as it arrived *(11:23)*
- [ ] `181` What working means *(6:50)*
- [ ] `182` From a request to a running system *(8:54)*
- [ ] `183` Follow one shipment *(7:53)*
- [ ] `184` The solution in nine steps *(9:45)*
- [ ] `185` The architecture on one map *(4:51)*

#### Section 32: The Enterprise Reality: Tutorial World vs. Bank World
- [ ] `186` Where tutorials stop helping *(7:04)*
- [ ] `187` Tutorial world vs bank world *(8:36)*
- [ ] `188` How the ask arrives *(6:03)*
- [ ] `189` The whiteboard and the kick-off call *(10:03)*
- [ ] `190` A case today, four people *(5:18)*
- [ ] `191` Success and the stop rule *(4:05)*
- [ ] `192` Real time, honestly *(7:06)*

#### Section 33: Capstone Graduation
- [ ] `193` **[Final Milestone]** Final: Your FDE Case Study

---

## 🛠️ Technology Stack & Tools Reference

| Category | Tools & Libraries |
|---|---|
| **Programming & Validation** | Python 3.11+, Pydantic v2, Pydantic AI |
| **Cloud & Deployment** | Google Cloud Platform (GCP), Cloud Shell, gcloud CLI, Cloud Run, Docker |
| **LLM Providers & Gateways** | Google Gemini, OpenAI, Anthropic, Bifrost Gateway, Virtual Keys |
| **Agentic Frameworks** | Pydantic AI, Google ADK (Agent Development Kit), LangGraph |
| **Decision Models** | Jev (by TypeSafe), Google Vertex AI Decision Layer |
| **Observability & Tracing** | Pydantic Logfire, Spans, Traces, Distributed Tracing |
| **Security & Guardrails** | NeMo Guardrails, Input/Output Rail Validation, Red-Teaming |
| **Retrieval & Storage** | Qdrant Cloud Vector DB, MongoDB (NoSQL), Legacy HMS DBs |
| **Evaluation & Metrics** | RAGAS (Faithfulness, Precision, Recall), DeepEval, LLM-as-a-Judge |

---

## 🚀 Environment Setup & Quickstart

### 1. Prerequisites
- Python 3.11 or higher
- Google Cloud account (Free Tier / credits for Vertex AI and Cloud Run)
- Docker Desktop installed
- API Keys: Google Gemini / OpenAI / Anthropic / Qdrant / Logfire

### 2. Virtual Environment Setup
```bash
# Clone and enter the repository
https://github.com/vishalgoyal25/Forward-Deployed-Engineer-FDE-.git

# Create virtual environment
python -m venv .venv

# Activate virtual environment
# Windows (PowerShell):
.venv\Scripts\Activate.ps1
# Linux/macOS:
source .venv/bin/activate

# Upgrade pip
pip install --upgrade pip
```

### 3. Recommended Initial Dependencies
```bash
pip install pydantic pydantic-ai logfire qdrant-client deepeval ragas pymongo google-cloud-aiplatform
```

---

## 📝 Study Notes & Key Takeaways Log

Use this section to record weekly reflections, key architectural patterns, and lessons learned from the client role plays:

* **Week 1 (FDE Foundations & Discovery):**  
  * *Key lesson:* An FDE must always clarify the difference between what a client *asks for* and what they *actually need*. Focus on the business value rather than the raw model specs.
* **Week 2 (Pydantic AI & Structured Workflows):**  
  * *Key lesson:* Never let an LLM return unparsed text to an enterprise system. Use Pydantic schemas with strict validators, retries, and dependency injection (`RunContext`).
* **Week 3 (Security & Governance):**  
  * *Key lesson:* Always configure input/output guardrails (NeMo) before exposing an application to client users. Prepare a CISO review pack upfront.

---

*Keep this repository updated as you complete assignments, build projects, and prepare for your AI Forward Deployed Engineer career!*
