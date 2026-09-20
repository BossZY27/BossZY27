<a id="readme-top"></a>

<div align="center">

<picture>
  <source media="(prefers-reduced-motion: reduce)" srcset="./assets/automation-core-static.svg" />
  <img src="./assets/automation-core.svg" width="100%" alt="BossZY27 neon automation engineer banner" />
</picture>

<p>
  <a href="https://github.com/BossZY27?tab=repositories"><img src="https://img.shields.io/badge/Explore-My_Repositories-22D3EE?style=for-the-badge&logo=github&logoColor=050816" alt="Explore my repositories" /></a>
  <img src="https://img.shields.io/badge/Focus-Automation_Engineering-A855F7?style=for-the-badge" alt="Focus: Automation Engineering" />
  <img src="https://img.shields.io/badge/Builder-Solo_End--to--End-0EA5E9?style=for-the-badge" alt="Solo end-to-end builder" />
</p>

**I turn repetitive business workflows into reliable automation, bots, and AI-assisted systems.**

`Data Ingestion` · `API Integration` · `Workflow Automation` · `AI Agents` · `Dashboards` · `Notifications`

</div>

## About Me

I am a solo software builder focused on automation engineering and bot development. I work end to end: understanding a manual process, designing the workflow, connecting data sources, implementing the system, and making the result observable through logs, notifications, reports, or dashboards.

- ⚙️ **Workflow Automation**: scheduled jobs, validation, deduplication, state machines, and human approval steps
- 🤖 **Bots and AI**: Telegram bots, AI-assisted document processing, RAG, vision, and structured extraction
- 🔌 **System Integration**: Google Workspace, REST APIs, Supabase, databases, storage, and messaging channels
- 🖥️ **Full-Stack Delivery**: web dashboards, mobile apps, backend services, desktop utilities, and deployment workflows
- 🛡️ **Operational Thinking**: retries, audit trails, role-based access, dry runs, recovery paths, and secure configuration

> [!NOTE]
> I am currently targeting **Automation Engineer / Bot Developer** opportunities where I can convert real business operations into maintainable software systems.

## Automation Workflow

```mermaid
%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#081526', 'primaryBorderColor': '#22d3ee', 'primaryTextColor': '#e6faff', 'lineColor': '#a855f7', 'secondaryColor': '#160d2b', 'tertiaryColor': '#07101d'}}}%%
flowchart LR
    A[Trigger] --> B[Collect Data]
    B --> C{Validate}
    C -->|Valid| D[Transform and Automate]
    C -->|Needs Review| E[Human Checkpoint]
    E --> D
    D --> F[(Database or Storage)]
    F --> G[Notify and Report]
    G --> H[Monitor and Improve]
```

## Selected Automation Work

Private systems are shown as sanitized summaries. Public projects link directly to source code.

<table>
<tr>
<td width="50%" valign="top">

### [Classroom Automation Pipeline](https://github.com/BossZY27/webscraping-classroom-ai)

Synchronizes Google Classroom and Drive resources, removes duplicate files with content hashing, stores metadata, schedules recurring updates, generates AI summaries, and exports organized learning packages.

`Python` `FastAPI` `Google APIs` `SQLite` `APScheduler` `Gemini/OpenAI/Ollama`

<sub>Public repository · sanitized source snapshot</sub>

</td>
<td width="50%" valign="top">

### E-Receipt Reconciliation Bot

Reads structured information from incoming emails, compares receipt values, records Match/Unmatch results in Google Sheets, and sends automated LINE or email alerts on a schedule.

`Google Apps Script` `Gmail` `Google Sheets` `Triggers` `Notifications`

<sub>Private project · sanitized technical summary</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [TikTok Analytics Workflow](https://github.com/BossZY27/tiktok-analytics)

Combines multi-account metrics, role-based access, data imports, synchronization workers, revenue workflows, and AI-assisted insights in one dashboard.

`Next.js` `TypeScript` `Prisma` `PostgreSQL` `Data Pipelines`

<sub>Public repository · MVP under active development</sub>

</td>
<td width="50%" valign="top">

### [AI Scheduling Assistant](https://github.com/BossZY27/secretary-bot)

Accepts text or schedule images, extracts structured appointments with AI vision, checks free time, stores events, and delivers morning summaries and appointment reminders through Telegram.

`Python` `Telegram Bot` `Gemini` `SQLite` `Scheduled Jobs`

<sub>Public repository · solo project</sub>

</td>
</tr>
</table>

<p align="center">
  <a href="https://github.com/BossZY27/loongmordek-auto-sheets">Loongmordek Auto Sheets</a> ·
  <a href="https://github.com/BossZY27/thai-rag-api">Thai RAG API</a> ·
  <a href="https://github.com/BossZY27/forex-order-watcher">Forex Order Watcher</a>
</p>

<details>
<summary><b>More Systems I Have Built</b></summary>

<br />

- **Content Operations Automation**: AI content parsing, Google Sheets approval states, and Make-ready publishing queues
- **TeleSales Workflow Platform**: lead operations, reminders, reporting, spreadsheet imports, and Google Sheets synchronization
- **Backup and Recovery Automation**: MinIO/rclone scheduling, retention, locking, health checks, dry runs, and restore workflows
- **Low-Latency Desktop Tooling**: MPD stream monitoring, segment prediction, packaged Windows releases, and runtime diagnostics
- **Secure AI Workspace Bridge**: local-first MCP access with path controls, rate limits, approvals, and sandboxed job execution
- **Full-Stack Business Platforms**: loyalty, franchise operations, construction milestones, analytics, and group-ordering systems

</details>

## Technology Stack

<div align="center">

### Languages

![Python](https://img.shields.io/badge/Python-050816?style=for-the-badge&logo=python&logoColor=22D3EE)
![TypeScript](https://img.shields.io/badge/TypeScript-050816?style=for-the-badge&logo=typescript&logoColor=22D3EE)
![JavaScript](https://img.shields.io/badge/JavaScript-050816?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Dart](https://img.shields.io/badge/Dart-050816?style=for-the-badge&logo=dart&logoColor=22D3EE)
![SQL](https://img.shields.io/badge/SQL-050816?style=for-the-badge&logo=postgresql&logoColor=A855F7)
![PowerShell](https://img.shields.io/badge/PowerShell-050816?style=for-the-badge&logo=powershell&logoColor=22D3EE)

### Automation, Backend, and AI

![FastAPI](https://img.shields.io/badge/FastAPI-050816?style=for-the-badge&logo=fastapi&logoColor=22D3EE)
![Next.js](https://img.shields.io/badge/Next.js-050816?style=for-the-badge&logo=nextdotjs&logoColor=FFFFFF)
![Flutter](https://img.shields.io/badge/Flutter-050816?style=for-the-badge&logo=flutter&logoColor=22D3EE)
![Supabase](https://img.shields.io/badge/Supabase-050816?style=for-the-badge&logo=supabase&logoColor=3ECF8E)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-050816?style=for-the-badge&logo=postgresql&logoColor=A855F7)
![Google Cloud](https://img.shields.io/badge/Google_APIs-050816?style=for-the-badge&logo=googlecloud&logoColor=22D3EE)
![Telegram](https://img.shields.io/badge/Telegram_Bots-050816?style=for-the-badge&logo=telegram&logoColor=22D3EE)
![Gemini](https://img.shields.io/badge/Gemini_AI-050816?style=for-the-badge&logo=googlegemini&logoColor=A855F7)

</div>

## Currently Designing

**Sales Lead Detection and Follow-Up Automation**, a proposed system for identifying relevant sales opportunities from Facebook posts using configurable products, keywords, locations, and quantities. The design includes A-D lead grading, screenshot capture and history, sales-team handoff, follow-up status, and daily reporting.

> [!IMPORTANT]
> This is currently presented as a **proposed system design**, not a completed production system. The ingestion method remains an implementation decision and is not assumed to use the Facebook API.

## Let's Build Something Useful

I am interested in automation projects where software can reduce repetitive work, connect disconnected tools, improve response time, and make operational data easier to act on.

<div align="center">

[![Repositories](https://img.shields.io/badge/Explore_Public_Repositories-050816?style=for-the-badge&logo=github&logoColor=22D3EE)](https://github.com/BossZY27?tab=repositories)

<sub>Designed around automation, reliability, and honest engineering evidence.</sub>

</div>
