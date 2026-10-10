# Awesome-Revops-Workflow-Orchestration

# Top RevOps Workflow Orchestration Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Revenue Process Automation, Data Orchestration & Self-Hosted RevOps Engines*  
**Last updated: October 2026**

This repository tracks notable **commercial RevOps workflow orchestration platforms** and **open-source projects** that automate revenue operations — lead routing, CRM hygiene, deal scoring, pipeline monitoring, and cross-system data synchronization — from enterprise iPaaS to self-hosted agentic GTM operating systems.

**Examples** include Salesforce Revenue Orchestration, Syncari, LeanData, Tonkean, Full Circle Insights, CaliberMind, Chili Piper, Openprise, Troops, and RevOps.io (the category leaders).

**Open-source emphasis**: RevOps workflow orchestration is a rapidly growing open-source domain. **RevenueOS** leads as a self-hosted revenue department for one business — workers analyze website, ads, leads, and mailbox, then execute only approved work with measured outcomes . **SDRbot** brings a terminal-native RevOps agent that automates CRM tasks, prospect research, and sales workflows with your own API keys, fully local and completely free . **Synapse Agentic GTM OS** deploys a 17-agent AI organization with agent-to-agent delegation, human-in-the-loop approval, and RAG memory . **Focal CRM Sales** delivers a Laravel-based revenue acceleration engine with multi-pipeline Kanban, CPQ quoting, and intelligent lead routing . **helio** provides an open-source growth platform with CDP, segmentation, and cross-channel journeys . **Lead-to-CRM Pipeline** automates lead cleaning, scoring, deduplication, and HubSpot sync entirely within Google Sheets . **dagu** and **Cadence** provide durable workflow orchestration foundations . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[LeanData](https://www.leandata.com/)**  
  **The enterprise standard for lead-to-account matching and routing** — match leads to accounts, route to correct owners, and orchestrate revenue workflows with AI-powered automation. **Best for enterprise revenue operations teams**.

- **[Syncari](https://syncari.com/)**  
  **Revenue data orchestration platform** — sync, dedupe, and enrich customer data across CRM, ERP, and marketing systems with a visual workflow builder. **Best for multi-system revenue data unification**.

- **[Tonkean](https://tonkean.com/)**  
  **No-code process orchestration for revenue teams** — build custom intake, routing, and approval workflows across CRM, Slack, and email. **Best for operations teams wanting no-code automation**.

- **[CaliberMind](https://calibermind.com/)**  
  **Revenue data platform** — unifies marketing, sales, and product data for attribution, analytics, and orchestration. **Best for B2B revenue intelligence**.

- **[Chili Piper](https://www.chilipiper.com/)**  
  **Meeting scheduling and lead routing** — instantly route inbound leads to the right rep and book meetings automatically. **Best for inbound lead conversion**.

- **[Openprise](https://www.openprise.com/)**  
  **RevOps data automation platform** — dedupe, enrich, normalize, and route data across the revenue stack. **Best for data hygiene and orchestration at scale**.

- **[Full Circle Insights](https://www.fullcircleinsights.com/)**  
  **Funnel metrics and attribution for Salesforce** — native CRM analytics for pipeline velocity and marketing attribution. **Best for Salesforce-native revenue analytics**.

- **[Troops](https://www.troops.ai/)**  
  **Revenue operations automation** — Slack-native alerts, deal updates, and workflow automation for sales teams. **Best for Slack-centric revenue teams**.

- **[RevOps.io](https://revops.io/)**  
  **Revenue operations platform** — lead routing, data orchestration, and workflow automation.

- **[Salesforce Revenue Orchestration](https://www.salesforce.com/)**  
  **Salesforce's native orchestration** — flows, process builder, and Einstein automation for revenue workflows. **Best for Salesforce customers**.

## Open-Source GitHub Projects

### Self-Hosted RevOps Platforms

- **[RevenueOS](https://github.com/unempyd/revenueos)**  
  **Self-hosted revenue department for one business**, MIT licensed . **Connect your business. RevenueOS finds opportunities, executes approved revenue work, and measures what happened** . **Workers**: SEO auditor (crawl defects, authority gap), Ads auditor (wasted spend, over-pacing), Discover (prospects from lead lists), Outreach (first-touch drafts, sends with daily cap and unsubscribe), Inbox (replies, bounces, STOP requests), Content (Claude produces deliverables), Monitor (Hacker News relevance gate), Measure (records every outcome) . **Approval-first** — nothing sends, publishes, or spends until you approve it . **Verified runtime proof** — crawled 12 pages, queued 6 content opportunities, approved one, Claude produced a 14 KB deliverable in 1m 23s, measured outcome 0 → 1 (2026-09-12) . **Requirements**: Python 3.12+, Node 20+ . **LLM optional** — uses Anthropic API or signed-in Claude Code CLI; without either, deterministic checks still run . **Best for single-business revenue operations with approval-first automation**.

- **[SDRbot](https://github.com/NForce-ai/SDRbot)**  
  **Open-source, terminal-native RevOps agent**, open-source . **Automates CRM tasks, prospect research, and sales workflows using your own API keys** . **Fully local and completely free** . **CRM integrations** — connects to Salesforce, HubSpot, and other CRMs via MCP servers . **Email support** — OAuth (Gmail, Outlook) and generic IMAP/SMTP for Yahoo, AOL, iCloud, ProtonMail, Fastmail, Zoho, and more . **Tool scope control** — Standard (core CRM tools), Extended (custom objects), Privileged (admin/schema management) . **Non-interactive mode** for scripting, automation, and CI/CD: `sdrbot -n -p "List the top 10 deals closing this month"` . **JSON output** for programmatic consumption . **Auto-approve mode** for trusted workflows . **Best for terminal-native RevOps automation with full local control** .

- **[Synapse Agentic GTM OS](https://github.com/abdulfatiraziz/SynapseAgenticGTMOS)**  
  **The first open-source Agentic GTM Operating System**, MIT licensed . **17-agent AI organization** (CMO, SDR, Market Intel, RevOps, etc.) autonomously managing the revenue lifecycle . **Level 3 Collaborative Multi-Agent System** built on Google ADK and Vertex AI with Gemini 2.5 Flash . **Agent-to-Agent (A2A) Protocol** — agents delegate tasks to each other seamlessly . **Secure AI Framework (SAIF)** — guardrails against prompt injection and data leaks . **Human-in-the-Loop (HITL)** — high-stakes actions (emails, deals) pause for Slack approval . **RAG Memory** — agents remember past decisions using `pgvector` . **Live Monitoring Dashboard** — real-time metrics, trace waterfalls, and cost budgeting . **Zero Data Training** — your CRM data is never used to train Google models . **Best for teams wanting an autonomous multi-agent GTM organization**.

### CRM-Integrated RevOps Engines

- **[Focal CRM Sales](https://github.com/focalcrm/focal)**  
  **Revenue and deal acceleration engine for the Focal RevOps platform**, open-source . **Multi-pipeline Kanban tracking** — manage complex sales cycles across Enterprise, Self-Serve, and Channel pipelines with distinct stages . **Stage gate enforcement** — require fields (decision_maker_identified, budget_confirmed) before advancing deals . **Deal rotting & health scoring** — automatic vitality score (0-100) based on stage stall duration and recent touchpoints . **CPQ quoting** — line-item products with volume discounts, margin tracking, and branded PDF/web quotes . **Automated outbound cadences** — multi-day, multi-channel sequences with email, phone, and LinkedIn tasks . **Intelligent lead routing** — RoundRobin, Weighted, Territory, or SkillBased routing rules . **Weighted revenue forecasting & quotas** — real-time pipeline forecasts and rep quota attainment . **Tech stack**: Laravel 12/13, PHP 8.3 . **Best for Laravel-based RevOps platforms** .

- **[Lead-to-CRM Pipeline](https://github.com/SkyblyeAgency-Walid/lead-to-crm-pipeline)**  
  **Complete lead cleaning and CRM sync system in Google Sheets + Apps Script**, open-source . **Turns raw leads from 3 sources** (website forms, Meta lead ads, purchased lists) **into clean, scored, deduplicated HubSpot contacts** . **Pipeline**: Extract (parse raw JSON) → Transfer (staging sheet with Lead IDs) → Normalize (Title Case names, lowercase emails, +CC phones) → Score (0-100 quality with configurable deduction rules) → Route (Accept ≥70, Flag 40-69 for review, Reject <40) → HubSpot Sync (search-before-create, retry with backoff, full attempt logging) . **Features**: Bot detection via user-agent, purchased-list trust rule, human review queue with Approve/Reject, recovery workflow from archive, one-click menu operation, every stage re-run safe . **Nothing is ever deleted** — every lead ends up somewhere with a reason . **Best for teams wanting lead hygiene and HubSpot sync without dedicated infrastructure** .

### Workflow Orchestration Foundations

- **[dagu](https://github.com/dagu-org/dagu)**  
  **Lightweight workflow engine alternative to Airflow and Cron**, GPL-3.0 licensed with **2,595 GitHub stars** . **Define dependencies between commands in declarative YAML format** . **Natively supports running containers, making HTTP requests, and executing commands over SSH** . **Best for teams wanting simple, self-hosted workflow orchestration** .

- **[Cadence](https://github.com/uber/cadence)**  
  **Open-source, fault-tolerant workflow orchestration engine from Uber**, Apache-2.0 licensed . **Durable workflow functions survive process crashes, network partitions, and downstream outages** . **Code-first workflows in Go, Java, and Python** . **CNCF Sandbox project governed by Linux Foundation** . **Targets 2,000+ domains per cluster with isolation guarantees** . **Best for mission-critical revenue workflows requiring durability** .

- **[Sparkflow](https://github.com/ilya-shevelev/sparkflow)**  
  **Distributed workflow orchestrator with native Apache Spark and Hadoop integration**, open-source . **A lightweight Go alternative to Apache Airflow** . **DAG-based workflows in YAML or Python** . **6 built-in executors**: Shell, Python, Docker, Spark, Hadoop MapReduce, HDFS . **Raft-based leader election with worker pool** . **Retry policies with dead letter queue** . **Best for data-heavy revenue workflows** .

### Additional Strong Open-Source Options

- **helio** — Open-source growth platform with CDP, segmentation, cross-channel journeys, email, and analytics. Self-hostable, data-sovereign. Sustains ~20,000 events/s at p95 81ms .
- **ZeroGTM** — Python-based enrichment engine with Google Maps scraper, contact mining, decision-maker ID, and email verification. BYOK architecture .
- **Lead Orchestra** — AI-powered automation engine for lead scraping, workflow orchestration, and data enrichment with browser automation and CRM sync .
- **GTM System Skeleton** — Repeatable GTM workflow with account ingestion, ICP scoring, enrichment logic, contact validation, and CRM-ready exports .
- **Odoo** — Open-source ERP with sales automation, CRM integration, warehouse, projects, accounting, and HR modules .

**Frameworks for building custom RevOps workflow orchestration solutions**: Combine **RevenueOS** for a self-hosted revenue department with approval-first workers and measured outcomes . Use **SDRbot** for terminal-native CRM automation and prospect research with full local control . Deploy **Synapse Agentic GTM OS** for a 17-agent autonomous GTM organization with human-in-the-loop approval . Integrate **Focal CRM Sales** for Laravel-based revenue acceleration with CPQ quoting and intelligent routing . Use **Lead-to-CRM Pipeline** for lead hygiene and HubSpot sync without infrastructure . Build on **dagu** or **Cadence** for durable workflow orchestration foundations . Note that true enterprise RevOps orchestration with visual process builders, cross-system data unification, and vendor-supported SLAs (LeanData, Syncari, Tonkean) remains primarily commercial territory; open-source stacks provide strong agent frameworks, CRM-integrated engines, and workflow foundations that require integration for complete revenue operations orchestration.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- RevOps orchestration platforms handle sensitive revenue data and may process PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA).
- **Approval-first design prevents costly mistakes** — RevenueOS and Synapse implement human-in-the-loop approval before any send, publish, or spend. This is essential for revenue workflows where errors have direct business impact .
- **Data quality determines orchestration quality** — CRM data hygiene is critical. Lead-to-CRM Pipeline demonstrates configurable scoring and deduplication before data reaches the CRM .
- **License considerations**: RevenueOS uses MIT , SDRbot is open-source , Synapse Agentic GTM OS uses MIT , Focal CRM Sales is open-source , dagu uses GPL-3.0 , and Cadence uses Apache-2.0 . Verify licensing against your use case before committing.
- The open-source ecosystem provides strong agent frameworks, CRM-integrated engines, and workflow foundations, but **visual process builders, cross-system data unification, and vendor-supported SLAs** remain primarily commercial offerings.
