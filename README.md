# Steve Kirby, J.D.

**A technology attorney who builds the AI he governs — and who ran the enterprise systems AI now
sits on top of.** Most AI-governance people have one of those legs; I have the triangle. I design
and ship secure, citation-grounded LLM systems *and* own the legal, privacy, and risk frameworks
that keep them defensible. Spokane, WA · open to remote / relocation / international.

- ⚖️ Practicing attorney (WA Bar, 2010) — technology, IP, privacy (HIPAA/GDPR), cyberlaw
- 🏛️ AI governance — NIST AI RMF, EU AI Act, model risk & audit; **IAPP AIGP** (certified 2026, No. 192392076)
- 🛠️ Hands-on builder — local-first RAG, anti-hallucination verification, evaluation harnesses
- 📊 Enterprise data & cloud architect (Nike, Costco) — the systems AI now runs on
- 🎤 Authored & taught a **WSBA-accredited CLE** on the ethical use of LLMs in law (2025)

---

### 🔭 Featured work — assurance results, not demos

**[wa-legal-ai-showcase](https://github.com/skirby359/wa-legal-ai-showcase)** — Air-gapped legal-research AI for Washington State law *(public showcase of the architecture; the production system, corpus, and prompts are private)*.
A 7-stage retrieval pipeline (rewrite → retrieve → rerank → pack → answer → **verify** → render)
over **428K legal authorities** that refuses to hallucinate: every citation is verified against the
corpus before it reaches the user. On a 150-question attorney-reviewed gold set it scores
**98%+ citation accuracy with zero hallucinations**, fully on-prem — the kind of control a
Head-of-AI-Risk has to specify *and* be able to verify.
`Python · FastAPI · PostgreSQL/pgvector · Ollama · Claude · Docker`

**[wa-cite-check](https://github.com/skirby359/wa-cite-check)** — Catches the mistake getting lawyers sanctioned.
Point it at a motion (`.docx`/`.pdf`) and it flags every **fabricated, mis-named, or wrong-year citation**,
plus authorities that have been overruled or repealed — fully offline. An optional LLM judge checks
whether each cited authority actually *supports* the proposition it's cited for.
`Python · SQLite · click · LLM-as-judge`

**[muni-bond-ai-showcase](https://github.com/skirby359/muni-bond-ai-showcase)** — The same anti-hallucination architecture, re-pointed at federal tax-exempt **municipal bond law** (IRC, Treasury Regs, IRS guidance, Tax Court).
On a 12-question attorney-authored gold set: **zero invented citations, 98.9% claim-to-evidence
coverage, 100% out-of-domain refusal** — proof the methodology is a reusable platform across
regulated domains, not a one-off.
`Python · FastAPI · PostgreSQL/pgvector · local LLMs (vLLM/llama.cpp) · Claude`

**[complyguard-showcase](https://github.com/skirby359/complyguard-showcase)** — Compliance-by-design, automated.
Crawls an e-commerce site and audits it against state + federal consumer-protection law across **all 52 US jurisdictions** —
a 71-rule engine plus a Claude analysis pipeline that returns risk scores, **statutory citations**, and
plain-English fixes. A full-stack product, not a demo: authentication, Stripe billing, background jobs, PDF/DOCX reports.
`Next.js · TypeScript · PostgreSQL/Prisma · Stripe · Playwright · Claude`

---

### 🧰 Tech I build with

`Python` · `Claude` · `Ollama (Llama / Mistral / DeepSeek / Qwen)` · `pgvector` · `FastAPI` ·
`Docker` · `AWS & on-prem/local` · RAG · evaluation & guardrails · model fine-tuning

### 🤝 What I'm looking for

AI governance sits where legal risk, enterprise systems, and real deployment meet — I'm not
changing careers, these threads converged. I'm looking to **own an organization's AI-governance
program end to end** as an operating leader (AI governance, responsible-AI engineering, or
trustworthy AI in a regulated domain), and I take on **fractional / interim Chief-AI-Risk**
engagements.

📫 **kirby@tikorconsulting.com** · [LinkedIn](https://www.linkedin.com/in/kirbysteve) · [Tikor Consulting](https://www.tikorconsulting.com)
