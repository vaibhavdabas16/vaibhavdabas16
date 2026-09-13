# Vaibhav Dabas

Final-year BTech CS & AI student at Plaksha University. I build LLM agent systems and ship them to real users, and I contribute to open-source benchmarks and tooling for AI agents.

Looking for an AI research internship starting January 2027 (remote, part-time) and full-time May to July 2027.

[LinkedIn](https://www.linkedin.com/in/vaibhav-dabas-5a5572275/) · vaibhav16dabas@gmail.com

## Open source

**[TIGER-AI-Lab/ClawBench](https://github.com/TIGER-AI-Lab/ClawBench)** (Waterloo). Benchmark for browser agents on daily tasks. Six merged PRs so far, mostly in the runner, judge, and batch evaluation paths: bounding container waits so one wedged run can't stall a batch, making a judge outage count as unjudged rather than an agent failure, resolving the container engine on use instead of at import, and consolidating the scoring docs. More open: a Steel browser runtime, a task-source adapter layer, and a WebVoyager task loader.

**[firecrawl/anydoc](https://github.com/firecrawl/anydoc)**. Rust document-to-Markdown converter. Outlook `.msg` reading, spreadsheet extent fixes, and an XML escaping fix.

## Projects

**[Payment Incident Commander](https://github.com/vaibhavdabas16/payment-incident-commander)**. Ten agents behind a seventeen-state machine that detects payment failures, prices the damage, picks a recovery, and measures against a control group whether the fix worked. The policy gate is deterministic; no model sits in that path. [Live](https://payment-incident-commander.onrender.com).

**[SEC 10-K Risk Factor Delta Agent](https://github.com/vaibhavdabas16/sec-risk-deltaagent)**. Six-step agent, no framework, that diffs Risk Factor sections across consecutive 10-K filings and backs each change with news evidence. Pydantic contracts between every step so bad intermediates fail loudly.

**AURA** (private). Multi-agent RAG over financial filings. 42% on FinanceBench (23 points over baseline), 56% with human-in-the-loop review targeted at confidently-wrong answers, 92% on multi-hop with an agents-as-tools setup.

**[Automated Marksheet Grading](https://github.com/vaibhavdabas16/Automated-Marksheet-Grading-System)**. Reads handwritten exam sheets, grades against rubrics, runs code answers in a sandbox in under 100ms, and syncs to Google Classroom behind a TA approval gate. Used for batches of 120+ students.

**[TreeCanopySegmentor](https://github.com/vaibhavdabas16/TreeCanopySegmentor)**. Tree canopy instance segmentation for the Solafune challenge. Ranked 14 of 143+ teams. Benchmarked YOLOv8 through v12, Mask R-CNN, Mask2Former, SAM2, and RF-DETR on ~150 images.

**[Tweet-AI](https://tweet-ai-vaibhav.vercel.app/)**. Tweet refinement app on Next.js, Prisma, and Gemini. 50+ users in the first month.

## Tools

Python, TypeScript, Rust (learning). PyTorch, Pydantic, FastAPI, Next.js, PostgreSQL. Claude and Gemini APIs.
