<img src="assets/header.png" alt="Elisabeth Nnamani — AI Software Engineer · grounded RAG, multi-agent orchestration, offline-first AI · Lagos, NG" width="100%">

## 🛠️ &nbsp;What's running

<table>
<tr>
<td width="64" align="center"><img src="assets/icons/atlas.png" width="46"></td>
<td>
<b><a href="https://atlas-ai-taupe.vercel.app">Atlas AI</a></b>&nbsp;&nbsp;<img src="assets/pills/live.png" height="20">&nbsp;<img src="assets/pills/apache.png" height="20"><br>
Plain-English request → production data artifacts: dbt models, SQL, tests, docs. Six sequential agents grounded in a real DataHub catalog, with two human approval gates that are genuine orchestrator pauses — they survive a restart.<br>
<sub><code>FastAPI</code> <code>async SQLAlchemy</code> <code>WebSockets</code> <code>Groq</code> <code>DataHub</code> <code>Next.js</code></sub>
</td>
</tr>
<tr>
<td align="center"><img src="assets/icons/prismos.png" width="46"></td>
<td>
<b><a href="https://prism-os-jade.vercel.app">PrismOS</a></b>&nbsp;&nbsp;<img src="assets/pills/live.png" height="20">&nbsp;<img src="assets/pills/qwen.png" height="20"><br>
Point it at a codebase, describe a feature, get the code <i>and</i> the argument that produced it. Seven agents required to disagree, every conflict written to a log, QA holding a binding ship/revise verdict.<br>
<sub><code>LangGraph</code> <code>FastAPI</code> <code>Qwen3-235B</code> <code>Next.js 14</code> <code>Supabase</code> <code>Alibaba Cloud</code></sub>
</td>
</tr>
<tr>
<td align="center"><img src="assets/icons/farmtwin.png" width="46"></td>
<td>
<b><a href="https://github.com/Elisabeth56/FarmTwin">FarmTwin</a></b>&nbsp;&nbsp;<img src="assets/pills/offline.png" height="20">&nbsp;<img src="assets/pills/adtc.png" height="20"><br>
Agronomic advisor for a Nigerian smallholder maize farm. Model, vector index and knowledge base all on-device — zero network calls at runtime, on a 2014 MacBook with 8&nbsp;GB of RAM. Every answer cited back to NAERLS, IITA, CIMMYT or FAO.<br>
<sub><code>llama.cpp</code> <code>Qwen2.5-3B Q4_K_M</code> <code>sqlite-vec</code> <code>FastAPI</code> <code>React</code></sub>
</td>
</tr>
<tr>
<td align="center"><img src="assets/icons/finsight.png" width="46"></td>
<td>
<b><a href="https://finsight-red-two.vercel.app">FinSight AI</b>&nbsp;&nbsp;<img src="assets/pills/flagship.png" height="20"><br>
Personal finance dashboard with RAG chat over your own transactions.<br>
<sub><code>Next.js</code> <code>FastAPI</code> <code>LlamaIndex</code> <code>LLaMA 3</code> <code>PostgreSQL</code></sub>
</td>
</tr>
<tr>
<td align="center"><img src="assets/icons/flowmind.png" width="46"></td>
<td>
<b><a href="https://flowmind-sage.vercel.app">FlowMind</b>&nbsp;&nbsp;<img src="assets/pills/flagship.png" height="20"><br>
Workflow automation OS — the repetitive parts of a work week, delegated.<br>
<sub><code>Next.js</code> <code>Supabase</code> <code>LangChain</code> <code>Mistral</code> <code>shadcn/ui</code></sub>
</td>
</tr>
</table>

## 🧭 &nbsp;Three decisions I'd defend

> [!IMPORTANT]
> **Grounding beats generation.**
> Atlas exists because an LLM asked for SQL will confidently invent a schema. Anchoring it to the organisation's real catalog is the whole difference between a demo and something a data team would run in production.

> [!NOTE]
> **A benchmark you grade yourself is worthless if you grade it kindly.**
> I scored FarmTwin at ~98.8, re-read the rubric properly, and re-graded it down to 87.6. The second number is the one in the repo.

> [!TIP]
> **Cut the feature you want most if it fails the gate.**
> Pidgin voice input was the thing I most wanted in FarmTwin — I'm a native speaker. I set a 40% WER threshold *before* testing, both candidate models missed it, the feature shipped English-only, and the reasoning went into ADR-011.

## 🧰 &nbsp;Stack

<img src="assets/stack.png" alt="Frontend: Next.js, React, TypeScript, Tailwind, Framer Motion, shadcn/ui · Backend: FastAPI, Python, Node.js, PostgreSQL, Supabase, WebSockets · AI layer: LangGraph, LangChain, LlamaIndex, llama.cpp, RAG pipelines, Groq, Qwen, Mistral · Infra: Vercel, Docker, Render, Neon, Alibaba Cloud, CI/CD" width="100%">

## 🌍 &nbsp;Also true

- 🏁 &nbsp;I run through hackathons — **Qwen Cloud** (Agent Society), **Africa Deep Tech Challenge**, because a hard deadline is the fastest way to find out whether an architecture actually holds.
- 🧪 &nbsp;Freelance: AI apps, automations, SaaS MVPs, dashboards, internal tools.
- 📌 &nbsp;I keep the caveats public. Every repo README says what isn't verified yet.

<img src="assets/footer.png" alt="elisabethnnamani.dev · LinkedIn /in/elisabethnnamani · X @elisynthdev · nnamanielisabeth@gmail.com" width="100%">

<p align="center">
  <a href="https://elisabethnnamani.dev">Portfolio</a> ·
  <a href="https://linkedin.com/in/elisabethnnamani">LinkedIn</a> ·
  <a href="https://x.com/elisynthdev">X</a> ·
  <a href="mailto:hello@elisabethnnamani.dev">Email</a>
</p>
