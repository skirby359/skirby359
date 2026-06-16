<!--
  GitHub PROFILE README.
  To publish: create a repo named exactly `skirby359` (github.com/skirby359/skirby359),
  add this as README.md, and GitHub renders it at the top of your profile.
-->

# Steve Kirby, J.D.

**Technology attorney who builds the AI he advises on.** I design and ship secure,
citation-grounded LLM systems — and own the governance, privacy, and risk frameworks
that keep them defensible. Spokane, WA · open to remote / relocation / international.

- ⚖️ Practicing attorney (WA Bar, 2010) — technology, IP, privacy (HIPAA/GDPR), cyberlaw
- 🛠️ Hands-on builder — local-first RAG, anti-hallucination verification, evaluation harnesses
- 📊 20+ years of enterprise data architecture (Nike, Costco) before AI was the easy part
- 🎓 In progress: IAPP **AIGP** (AI Governance) · **ISC2 CC** · Azure **AI-900**

---

### 🔭 Featured work

**[wa-legal-ai-showcase](https://github.com/skirby359/wa-legal-ai-showcase)** — Air-gapped legal research assistant for Washington State law *(public showcase of the architecture; the production system and its corpus/prompts are private)*.
A 7-stage retrieval pipeline (rewrite → retrieve → rerank → pack → answer → **verify** → render)
over **428K legal authorities** that refuses to hallucinate: every citation is verified against the
corpus before it reaches the user. On a 150-question attorney-reviewed gold set it scores
**98%+ citation accuracy with zero hallucinations**. Runs fully on-prem — no client data leaves the building.
`Python · FastAPI · PostgreSQL/pgvector · Ollama · Claude · Docker`

**[wa-cite-check](https://github.com/skirby359/wa-cite-check)** — Catches the mistake that's getting lawyers sanctioned.
Point it at a motion (`.docx`/`.pdf`) and it flags every **fabricated, mis-named, or wrong-year citation**,
plus authorities that have been overruled or repealed — fully offline. An optional LLM judge checks
whether each cited authority actually *supports* the proposition it's cited for.
`Python · SQLite · click · LLM-as-judge`

---

### 🧰 Tech I build with

`Python` · `Claude` · `Ollama (Llama / Mistral / DeepSeek / Qwen)` · `pgvector` · `FastAPI` ·
`Docker` · `AWS & on-prem/local` · RAG · evaluation & guardrails · model fine-tuning

### 🤝 What I'm looking for
An operating role where law and applied AI meet — AI governance, responsible-AI engineering,
or building trustworthy AI in a regulated domain.

📫 **kirby@tikorconsulting.com** · [LinkedIn](https://www.linkedin.com/in/kirbysteve) · [Tikor Consulting](https://www.tikorconsulting.com)
