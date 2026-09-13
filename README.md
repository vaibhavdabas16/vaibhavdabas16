<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6&height=220&section=header&text=Vaibhav%20Dabas&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=LLM%20agents%20that%20hold%20up%20outside%20a%20notebook&descAlignY=58&descSize=20" width="100%"/>

<a href="https://www.linkedin.com/in/vaibhav-dabas-5a5572275/" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:vaibhav16dabas@gmail.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://vaibhavdabas.vercel.app" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Portfolio-111827?style=for-the-badge&logo=vercel&logoColor=white" /></a>
<a href="https://payment-incident-commander.onrender.com" target="_blank" rel="noopener noreferrer"><img src="https://img.shields.io/badge/Incident%20Commander-16a34a?style=for-the-badge&logo=razorpay&logoColor=white" /></a>

<br/><br/>

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=26&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&multiline=true&width=820&height=100&lines=%F0%9F%A4%96+Building+multi-step+LLM+agents+and+shipping+them;%F0%9F%94%A7+Contributor+%40+TIGER-AI-Lab%2FClawBench+%C2%B7+firecrawl%2Fanydoc;%F0%9F%8E%93+CS+and+AI+%40+Plaksha+University+%C2%B7+Class+of+2027;%F0%9F%94%8E+Open+to+AI+research+internships+from+Jan+2027" />

</div>

### 👋 About me

I'm Vaibhav, a final-year Computer Science and AI student at Plaksha University. I build LLM systems that have to hold up outside a notebook: agents that plan and call tools, retrieval over messy documents, and evaluation that catches the model being wrong before a user does. I'd rather a system fail loudly than quietly return something wrong.

- 🎓 B.Tech Computer Science & AI @ **Plaksha University**, graduating 2027
- 🧠 Currently shipping: agentic pipelines with deterministic policy gates, and evaluation tooling for browser agents
- 🔧 Six merged PRs into **TIGER-AI-Lab/ClawBench** (Waterloo), plus contributions to **firecrawl/anydoc**
- 🏆 Ranked 14 of 143+ teams in the Solafune tree canopy segmentation challenge
- 🔎 Looking for an AI research internship: remote part-time from Jan 2027, full-time May to Jul 2027
- 💬 Ask me about LLM agents, RAG, structured outputs, human-in-the-loop systems, or computer vision
- 📫 vaibhav16dabas@gmail.com

---

### 🚀 Flagship builds

<table>
<tr>
<td width="50%" valign="top">

#### 💳 <a href="https://github.com/vaibhavdabas16/payment-incident-commander" target="_blank" rel="noopener noreferrer">Payment Incident Commander</a>
**An autonomous payment reliability and revenue recovery agent.** Payments start failing; it detects it, works out why, prices the damage, picks the safest way out, and proves against a control group whether its own fix worked.

- Ten agents, one responsibility each, driven by a seventeen-state machine
- Policy gate is deterministic: approve, clamp, escalate, or deny, with no model in that path
- Three independent statistical tests must agree before an incident opens
- Undoes its own fix and hands over when the numbers say it didn't work

🔗 <a href="https://payment-incident-commander.onrender.com" target="_blank" rel="noopener noreferrer">Live system</a> · <a href="https://github.com/vaibhavdabas16/payment-incident-commander/blob/main/docs/ARCHITECTURE.md" target="_blank" rel="noopener noreferrer">Architecture</a>

</td>
<td width="50%" valign="top">

#### 📄 <a href="https://github.com/vaibhavdabas16/sec-risk-deltaagent" target="_blank" rel="noopener noreferrer">SEC 10-K Risk Factor Delta Agent</a>
**Diffs Risk Factor sections across consecutive 10-K filings** and enriches each change with news evidence, emitting an investor memo plus a typed state dump.

- Six-step agent built with no agent framework
- Pydantic contracts between every step, so a malformed intermediate fails loudly instead of silently corrupting the memo
- Graceful degradation for EDGAR rate limits, single-filing companies, and search-API fallback
- Every claim in the output labelled with source-backed confidence

🔗 <a href="https://github.com/vaibhavdabas16/sec-risk-deltaagent" target="_blank" rel="noopener noreferrer">Repo</a>

</td>
</tr>
</table>

---

### 🧩 Open source

| Repo | What I've done |
|---|---|
| <a href="https://github.com/TIGER-AI-Lab/ClawBench/pulls?q=is%3Apr+author%3Avaibhavdabas16" target="_blank" rel="noopener noreferrer">**TIGER-AI-Lab/ClawBench**</a> (Waterloo) | Benchmark for browser agents on daily tasks. **6 merged PRs** in the runner, judge, and batch paths: bounded container waits so one wedged run can't stall a batch; a judge outage counts as unjudged, not an agent failure; container engine resolved on use instead of at import; a single source for the scoring docs. Open: a Steel browser runtime, a task-source adapter layer, a WebVoyager task loader |
| <a href="https://github.com/firecrawl/anydoc/pulls?q=is%3Apr+author%3Avaibhavdabas16" target="_blank" rel="noopener noreferrer">**firecrawl/anydoc**</a> | Rust document-to-Markdown converter. Outlook `.msg` reading, spreadsheet extent fixes, XML escaping fix |

---

### 🛠️ Other builds worth a look

| Project | What it does |
|---|---|
| <a href="https://github.com/vaibhavdabas16/Project-CLARUS" target="_blank" rel="noopener noreferrer">Project CLARUS</a> | Multi-agent RAG for financial Q&A and report generation: LLM-Compiler-style supervisor, adaptive retrieval with table understanding, analyst agent group, math/code executor, human-in-the-loop guardrails |
| AURA (private) | Multi-agent RAG over financial filings. 42% on FinanceBench (23 points over baseline), 56% with human review targeted at confidently-wrong answers, 92% on multi-hop with agents-as-tools |
| <a href="https://github.com/vaibhavdabas16/Automated-Marksheet-Grading-System" target="_blank" rel="noopener noreferrer">Automated Marksheet Grading</a> | Reads handwritten exam sheets, grades against rubrics, sandboxed code execution under 100ms, Google Classroom sync behind a TA approval gate. Used for 120+ student batches |
| <a href="https://github.com/vaibhavdabas16/TreeCanopySegmentor" target="_blank" rel="noopener noreferrer">TreeCanopySegmentor</a> | Tree canopy instance segmentation, Solafune challenge. Rank 14 of 143+ at 0.42 weighted mAP. Benchmarked YOLOv8 to v12, Mask R-CNN, Mask2Former, SAM2, RF-DETR on ~150 images |
| <a href="https://github.com/vaibhavdabas16/Drowsiness-Detection-with-Occlusion" target="_blank" rel="noopener noreferrer">Drowsiness Detection with Occlusion</a> | Lightweight drowsiness detector built for the occlusion cases that clean-benchmark models ignore |
| <a href="https://tweet-ai-vaibhav.vercel.app/" target="_blank" rel="noopener noreferrer">Tweet-AI</a> | Tweet refinement app on Next.js, Prisma, PostgreSQL, Gemini. 50+ users in month one, 45% 10-day retention |

---

### 🧰 Tech I work with

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

<div align="center">

<img src="https://streak-stats.demolab.com/?user=vaibhavdabas16&theme=tokyonight&hide_border=true" width="60%"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vaibhavdabas16/vaibhavdabas16/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/vaibhavdabas16/vaibhavdabas16/output/github-contribution-grid-snake.svg">
  <img alt="a snake eating my GitHub contribution graph" src="https://raw.githubusercontent.com/vaibhavdabas16/vaibhavdabas16/output/github-contribution-grid-snake.svg" width="90%"/>
</picture>

</div>
