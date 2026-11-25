<h1 align="center">Hi! I'm Vaibhav 🤖</h1>

<p align="center">
  I build LLM agent systems and contribute to the open-source tooling AI agents run on.<br/>
  <sub>Final-year CS &amp; AI at Plaksha University · Emergent Ventures grantee · ex-Barclays</sub>
</p>

<p align="center">
  <a href="https://github.com/search?q=author%3Avaibhavdabas16+is%3Apr+is%3Amerged+-user%3Avaibhavdabas16&type=pullrequests"><img alt="Merged open-source PRs" src="https://img.shields.io/github/issues-search?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Amerged%20-user%3Avaibhavdabas16&label=merged%20open-source%20PRs&color=2ea44f&style=for-the-badge&logo=github"/></a>
  <a href="https://vaibhavdabas.vercel.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-vaibhavdabas-111111?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/vaibhav-dabas-5a5572275/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Vaibhav%20Dabas-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:vaibhav16dabas@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-vaibhav16dabas-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>

## Things I've built

| Project | What it is |
|---|---|
| **[payment-incident-commander](https://github.com/vaibhavdabas16/payment-incident-commander)**<br/>[live system](https://payment-incident-commander.onrender.com) | An autonomous payment-reliability agent. When payments start failing it finds the cause, prices the damage, picks the safest fix, asks for approval where policy requires it, then checks the fix against an untouched control group and rolls back if it didn't work.<br/><sub>Python · Docker · JavaScript</sub> |
| **[Groundwork](https://github.com/vaibhavdabas16/Groundwork)** | A governed context layer and MCP server in front of a real DuckDB warehouse, so LLM data agents answer business questions with the right definitions. Every answer shows its SQL; ambiguous questions get a clarifying question and unsupported ones a refusal. Failed answers become fix proposals that ship only after evaluation and human approval.<br/><sub>Python · MCP · DuckDB · SQLGlot</sub> |
| **[TravelAgent](https://github.com/vaibhavdabas16/TravelAgent)**<br/>[try it](https://travel-agent-six-theta.vercel.app/) | Turns a plain-English trip request into a day-by-day itinerary. LLM agents handle the judgement, real APIs supply places, hours and flights, and a Google OR-Tools solver fits each day around opening hours and travel time.<br/><sub>Python · FastAPI · LangGraph · React · OR-Tools</sub> |
| **[minimi](https://github.com/vaibhavdabas16/minimi)** | A chat agent with one tool, web search. It answers fast, cites its sources, and remembers what you asked and when, so days later you can ask "is what you told me on 3 November still correct?"<br/><sub>TypeScript · Claude API</sub> |
| **[invoice-intelligence](https://github.com/vaibhavdabas16/invoice-intelligence)** | Reads a vendor document (PDF, scan or phone photo), decides whether it is an invoice and returns validated JSON, with an eval harness, failure analysis and per-document cost (under $0.001 an invoice).<br/><sub>Python · OpenAI API</sub> |
| **[sec-risk-delta-agent](https://github.com/vaibhavdabas16/sec-risk-delta-agent)** | Reads two consecutive SEC 10-K filings for any US-listed company, diffs the Risk Factors section, and backs each change with recent news in an investor-ready memo. Built from scratch with no agent frameworks.<br/><sub>Python · OpenAI API</sub> |
| **[Project CLARUS](https://github.com/vaibhavdabas16/Project-CLARUS)** | A multi-agent RAG system for financial Q&amp;A and report generation: a supervisor, adaptive retrieval over tables, an analyst agent group and a code executor, with human-in-the-loop guardrails.<br/><sub>Python · LangGraph · RAG</sub> |

## Open source

I fix bugs and build features in open-source infrastructure, mostly tooling for AI agents and data. Pull requests, counted live:

| Project | What it is | Merged | Open |
|---|---|---|---|
| [TIGER-AI-Lab/ClawBench](https://github.com/TIGER-AI-Lab/ClawBench/pulls?q=is%3Apr+author%3Avaibhavdabas16) | Benchmark for browser AI agents, from Waterloo | <img alt="merged PRs in TIGER-AI-Lab/ClawBench" src="https://img.shields.io/github/issues-search/TIGER-AI-Lab/ClawBench?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Amerged&label=merged&color=2ea44f"/> | <img alt="open PRs in TIGER-AI-Lab/ClawBench" src="https://img.shields.io/github/issues-search/TIGER-AI-Lab/ClawBench?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Aopen&label=open&color=blue"/> |
| [lance-format/lance](https://github.com/lance-format/lance/pulls?q=is%3Apr+author%3Avaibhavdabas16) | Open lakehouse format for multimodal AI | <img alt="merged PRs in lance-format/lance" src="https://img.shields.io/github/issues-search/lance-format/lance?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Amerged&label=merged&color=2ea44f"/> | <img alt="open PRs in lance-format/lance" src="https://img.shields.io/github/issues-search/lance-format/lance?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Aopen&label=open&color=blue"/> |
| [RunanywhereAI/runanywhere-sdks](https://github.com/RunanywhereAI/runanywhere-sdks/pulls?q=is%3Apr+author%3Avaibhavdabas16) | SDKs for running AI models on-device | <img alt="merged PRs in RunanywhereAI/runanywhere-sdks" src="https://img.shields.io/github/issues-search/RunanywhereAI/runanywhere-sdks?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Amerged&label=merged&color=2ea44f"/> | <img alt="open PRs in RunanywhereAI/runanywhere-sdks" src="https://img.shields.io/github/issues-search/RunanywhereAI/runanywhere-sdks?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Aopen&label=open&color=blue"/> |
| [fosrl/pangolin](https://github.com/fosrl/pangolin/pulls?q=is%3Apr+author%3Avaibhavdabas16) | Self-hosted secure access to apps and infrastructure | <img alt="merged PRs in fosrl/pangolin" src="https://img.shields.io/github/issues-search/fosrl/pangolin?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Amerged&label=merged&color=2ea44f"/> | <img alt="open PRs in fosrl/pangolin" src="https://img.shields.io/github/issues-search/fosrl/pangolin?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Aopen&label=open&color=blue"/> |
| [firecrawl/anydoc](https://github.com/firecrawl/anydoc/pulls?q=is%3Apr+author%3Avaibhavdabas16) | Converts Office, PDF and EPUB documents to clean Markdown | <img alt="merged PRs in firecrawl/anydoc" src="https://img.shields.io/github/issues-search/firecrawl/anydoc?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Amerged&label=merged&color=2ea44f"/> | <img alt="open PRs in firecrawl/anydoc" src="https://img.shields.io/github/issues-search/firecrawl/anydoc?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Aopen&label=open&color=blue"/> |
| [ksedgwic/clboss](https://github.com/ksedgwic/clboss/pulls?q=is%3Apr+author%3Avaibhavdabas16) | Automated manager for Core Lightning nodes | <img alt="merged PRs in ksedgwic/clboss" src="https://img.shields.io/github/issues-search/ksedgwic/clboss?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Amerged&label=merged&color=2ea44f"/> | <img alt="open PRs in ksedgwic/clboss" src="https://img.shields.io/github/issues-search/ksedgwic/clboss?query=author%3Avaibhavdabas16%20is%3Apr%20is%3Aopen&label=open&color=blue"/> |

Some merged work:

- [lance#11379](https://github.com/lance-format/lance/pull/11379). Lance: a commit that has already started is no longer cancelled when `retry_timeout` expires
- [ClawBench#316](https://github.com/TIGER-AI-Lab/ClawBench/pull/316). ClawBench: a host-side deadline on container waits, so one stuck run can't stall an overnight batch
- [ClawBench#314](https://github.com/TIGER-AI-Lab/ClawBench/pull/314). ClawBench: a bad `--judge` model no longer throws away a completed run
- [ClawBench#347](https://github.com/TIGER-AI-Lab/ClawBench/pull/347). ClawBench: each run records the code, corpus and agent revisions it used, so results can be reproduced

## Achievements

- **Top 50 of 32,000+**, Amazon ML Challenge '26
- **National Semi-Finalist**, Flipkart GRiD 8.0 (Sep 2026)
- **Emergent Ventures grant**, Mercatus Center: $15,000 for project ideation and development (Jul 2025)
- **#14 of 143+ teams**, Solafune Tree Canopy Instance Segmentation Challenge, 0.42 weighted mAP (Dec 2025)
- **3rd place**, Entrepreneurial Challenge Cup, Plaksha University (2026)
- **2nd of 100+**, Plaksha University hackathon

## Experience

- **Technology Developer Intern, Barclays** (Pune, Jun to Jul 2026). Shipped a feature-toggle framework and a .NET API to a platform serving ~5M clients, built a synthetic test-data pipeline to remove the dependency on production data, and fixed a route-guard vulnerability in a live production app.

## Tools I reach for

<p align="left">
  <img alt="Python, TypeScript, JavaScript, React, Next.js, Node.js, FastAPI, .NET, Tailwind, PyTorch, Docker, Postgres, Vercel, Git" src="https://skillicons.dev/icons?i=py,ts,js,react,nextjs,nodejs,fastapi,dotnet,tailwind,pytorch,docker,postgres,vercel,git&perline=7"/>
</p>

## Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vaibhavdabas16/vaibhavdabas16/output/github-snake-dark.svg"/>
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/vaibhavdabas16/vaibhavdabas16/output/github-snake.svg"/>
</picture>
