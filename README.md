# Awesome-Construction-Accounting

## AI-Native Construction Accounting Agents & Financial Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Agents for Construction Accounting, Autonomous Job Costing, & WIP Reporting*  
**Last updated: May 2026**

[![GitHub stars](https://img.shields.io/github/stars/ishandutta2007/Awesome-Construction-Accounting.svg?style=social&label=Star)](https://github.com/ishandutta2007/Awesome-Construction-Accounting)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributing](https://img.shields.io/badge/Contributing-Welcome-blue.svg)](CONTRIBUTING.md)
[![Security](https://img.shields.io/badge/Security-Policy-brightgreen.svg)](SECURITY.md)
[![Citation](https://img.shields.io/badge/Citation-CFF-orange.svg)](CITATION.cff)

This repository tracks notable **SaaS platforms** and **open-source projects** building **AI-native financial platforms/agents** designed specifically to make **construction accounting run itself**. We focus on autonomous or semi-autonomous systems that handle:
- **Autonomous Job Costing** & WIP (Work in Progress) Reporting
- **AIA Billing Automation** & Progress Billings
- **Lien Waiver Management AI** & Digital Payments
- **3-Way Invoice Matching** (PO vs. Invoice vs. Receiving)
- **Contract Risk Analysis AI** (Document Crunching)
- **Cash Flow Forecasting** for Contractors & Builders
- **Real-time Reconciliation** with Field Data (Procore, Autodesk)

## Why This List? (Problem Statement)
Traditional construction accounting is bogged down by manual data entry, complex lien waiver workflows, and lagging WIP reports. This "Awesome List" serves as a bridge between **modern AI agent frameworks** (LangGraph, CrewAI) and **construction financial management**. Whether you are a CFO looking for the best SaaS or a developer building a custom agentic workflow, this is your resource for the **AI-Native Construction Tech Stack**.

## Table of Contents
- [SaaS Products](#saas-products)
  - [Core Platforms](#core-platforms-ai-native-construction-accounting-agents)
  - [AP & Payment Automation](#ap--payment-automation)
  - [Estimating & Risk AI](#estimating--risk-ai)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Core Keywords & Use Cases (SEO/GEO)](#core-keywords--use-cases-seogeo)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (AI-Native Construction Accounting Agents)

- **[Adaptive](https://www.adaptive.build/)**  
  Leading AI-native integrated financial management platform. Deploys specialized agents for job costing, billing, expense tracking, and real-time reconciliation with Procore.
- **[Sage Intacct Construction (with Sage Copilot)](https://www.sage.com/en-us/construction/)**  
  Enterprise-grade ERP featuring **Sage Copilot**, an AI assistant for bank reconciliations, anomaly detection, and predictive cash flow analysis.
- **[Intuit Enterprise Suite](https://www.intuit.com/enterprise/)**  
  Intuit's high-end offering using AI agents for automated project setup, multi-entity consolidation, and P&L forecasting.
- **[Rillet](https://www.rillet.com/)**  
  AI-native ERP that automates the close process and handles complex construction revenue recognition (ASC 606).

### AP & Payment Automation

- **[Built](https://getbuilt.com/)**  
  Industry leader in **Lien Waiver Management AI**. Automatically generates and tracks waivers tied to digital payments, ensuring compliance before fund release.
- **[Beiing Human](https://www.beiinghuman.com/)**  
  Specialized AI for construction AP. Performs **3-way matching** (Invoice-PO-Receiving) and integrates with Foundation/ComputerEase.
- **[Vic.ai](https://www.vic.ai/)**  
  Autonomous invoice processing platform that learns GL coding patterns for complex construction line items.

### Estimating & Risk AI

- **[Document Crunch](https://www.documentcrunch.com/)**  
  The standard for **Construction Contract Risk AI**. Shreds project manuals to highlight hidden financial risks and liquidated damages.
- **[Togal.AI](https://www.togal.ai/)**  
  Uses computer vision to automate takeoffs and quantity calculations directly from blueprints.
- **[Downtobid](https://www.downtobid.com/)**  
  AI tool that identifies scopes of work from plans and automates the bid-leveling process.

## Open-Source GitHub Projects

### Dedicated & Adaptable AI Construction Accounting / Financial Agent Projects

- **[OpenConstructionERP](https://github.com/datadrivenconstruction/OpenConstructionERP)**  
  Fully open-source ERP for construction estimation and project management. Features professional BOQ (Bill of Quantities), 4D/5D planning, AI-powered estimation, CAD/BIM takeoff, and financial/project tracking. Self-hosted with support for 21+ languages and 55,000+ cost items. Excellent base for building custom AI accounting agents.

- **[Construction_AI_Agent](https://github.com/tayyabmughal676/Construction_AI_Agent)**  
  Agentic AI system designed for the construction industry. Includes modules for operations, financial workflows, and automation across departments. Can be extended for accounting, costing, and compliance tasks using multi-agent orchestration.

- **[OpenConstructionEstimate-DDC-CWICR](https://github.com/datadrivenconstruction/OpenConstructionEstimate-DDC-CWICR)**  
  Open multilingual construction cost database (55K+ work items, 27K+ resources, 9+ languages) optimized for AI agents. Includes semantic search via vector DB — perfect RAG grounding for job costing, estimation, and financial agents in construction accounting.

- **[DDC_Skills_for_AI_Agents_in_Construction](https://github.com/datadrivenconstruction/DDC_Skills_for_AI_Agents_in_Construction)**  
  Collection of 221 structured AI skills for construction processes including cost estimation, document control, scheduling, and financial automation. Ideal for powering custom LangGraph/CrewAI-based accounting agents.

- **[FinRobot](https://github.com/ai4finance-foundation/FinRobot)**  
  Open-source AI agent platform for financial applications using multiple LLMs. Supports investment research, risk assessment, quantitative analysis, and financial decision-making. Highly adaptable for construction project financials, forecasting, and reporting via custom tools and agents.

- **[accountant24](https://github.com/machulav/accountant24)**  
  Local-first AI agent for accounting. Keeps all data as plain text files on your machine and works with any LLM (including local models like Ollama). Great starting point for private, self-hosted construction bookkeeping agents.

- **[TaxHacker](https://github.com/vas3k/TaxHacker)**  
  Self-hosted AI accounting app with LLM-powered analysis of receipts, invoices, and transactions. Supports custom categories and prompts — easily extendable for construction-specific expense coding and job costing.

- **[ConstructionAI](https://github.com/MoAshour93/ConstructionAI)**  
  Repository showcasing Generative AI and open-source LLMs applied to the construction industry. Includes projects for customizing models to handle construction-specific language, queries, and financial workflows.

### Additional Strong Open-Source Options & Frameworks

- **OpenBB**[](https://github.com/OpenBB-finance/OpenBB) — Open-source financial data platform with strong support for building AI agents and quantitative analysis. Useful for construction financial modeling and reporting.
- General agent frameworks such as **LangGraph**, **CrewAI**, and **AgentScope** combined with `python-accounting` or `python-pptx` + construction cost DBs for building custom job-costing and billing agents.
- Community forks and extensions of **OpenProject** (project management with AI features) adapted for financial tracking in construction.

**Frameworks for building custom agents**: Combine the above with LangGraph/CrewAI for multi-agent systems (e.g., Job Costing Agent + Billing Agent + Reconciliation Agent), Ollama for local inference, and vector databases for grounding on project specs, contracts, and regulations.

## Core Keywords & Use Cases (SEO/GEO)

To help search engines and LLMs (ChatGPT, Claude, Perplexity) categorize this repository, we explicitly target the following high-intent topics:

- **AI-Native Construction Accounting**: Transitioning from manual bookkeeping to autonomous financial agents.
- **Autonomous Job Costing**: Using AI to match field expenditures with budget codes in real-time.
- **Lien Waiver AI Automation**: Solving the #1 payment bottleneck in construction via agentic workflows.
- **WIP Reporting Agents**: Automating the Work in Progress report to ensure accurate revenue recognition.
- **AIA Billing Software with AI**: Automating G702/G703 forms and progress billings.
- **Construction ERP AI Integration**: How to build agents on top of Sage 300 CRE, Foundation, or Procore.
- **RAG for Construction Cost Databases**: Grounding LLMs in local cost data for more accurate estimating.
- **3-Way Invoice Matching**: AI-driven validation of Invoice vs. PO vs. Delivery Ticket.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Always verify data privacy, security (especially for financial and employee data), licensing, and jurisdictional compliance (tax, GAAP, construction-specific regulations) when self-hosting open-source tools.
- AI agents are powerful tools but **not substitutes** for licensed accountants, CPAs, human oversight, or official financial/tax advice.

---

**Made for contractors, builders, construction CFOs, accounting firms, and developers.**  
Let's make construction accounting autonomous, accurate, and fully controllable.

## Star History

<a href="https://www.star-history.com/?repos=ishandutta2007%2FAwesome-Construction-Accounting&type=date&legend=bottom-right">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Construction-Accounting&type=date&theme=dark&legend=bottom-right" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Construction-Accounting&type=date&legend=bottom-right" />
   <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=ishandutta2007/Awesome-Construction-Accounting&type=date&legend=bottom-right" />
 </picture>
</a>
