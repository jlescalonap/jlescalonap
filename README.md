<h1 align="center">José Luis Escalona</h1>

<p align="center">
  <strong>Backend &amp; AI Engineer</strong> · Multi-tenant SaaS platforms<br>
  Founder &amp; Lead Engineer at <a href="https://tuquequesoft.com.br">Tuquequesoft</a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/jlescalonap/"><img src="https://img.shields.io/badge/LinkedIn-1B5E8C?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:jlescalonap@gmail.com"><img src="https://img.shields.io/badge/Email-2F3E4B?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://tuquequesoft.com.br"><img src="https://img.shields.io/badge/tuquequesoft.com.br-101B26?style=flat-square&logo=googlechrome&logoColor=white" alt="Website"></a>
</p>

<p align="center">
  <em>I design, build and operate platforms that run in production — multi-tenancy,<br>
  billing, auth, observability — and RAG agents with the evaluation harness to keep them honest.</em>
</p>

---

## What I'm building

### [Tekne](https://tekne.school) · `in production`

**Client project.** Multi-tenant learning platform, launched October 2026 and
built as sole engineer.

- **18,700+ automated tests** across 922 files — *more test code than
  production code*
- **Stripe-driven installment-billing engine**: state machine with an idempotent
  payment ledger, per-default grace windows, automated dunning, reversible
  enrollment and certificate retention while debt is outstanding
- Four languages with enforced translation parity (5,556 keys each, guarded by a
  test)
- Per-tenant branding, RBAC, encrypted per-tenant credentials, guest checkout

`NestJS` `Next.js 16` `React 19` `MongoDB` `Redis` `Stripe` `Railway` `Vercel`

### [EllaFirst](https://ellafirst.com/en-US) · `in production`

**Client project.** Geolocation-based marketplace for verified beauty and care
professionals, built end to end as sole developer — web and Expo mobile clients.
A second marketplace for the same client is finished and awaiting their launch.
~1,200 commits across both.

`Next.js` `React 19` `Prisma` `PostgreSQL` `Expo`

### layered_rag · `in development`

Multi-tenant RAG agent platform. Provider-agnostic LLM layer with a 5-adapter
fallback chain that **absorbed full model retirements at two providers with zero
code changes**. Deterministic evaluation harness plus LLM-as-judge scoring.

`Python` `LangChain` `ChromaDB` `FastAPI`

### Client web delivery · `in production`

Production sites for businesses in Brazil and the US through Tuquequesoft —
built for speed, SEO and conversion. Recent work includes a US contractor's
lead-generation platform with a 227-image optimization pipeline and local SEO
with structured data.

`Next.js` `TypeScript` `Tailwind`

---

## How I work

I build with AI agents under my direction, not instead of it: contracts written
before any implementation, adversarial multi-lens review of those contracts,
construction in parallel worktrees, and mutation testing with counted mutants.
Every line is reviewed and owned.

Operating rules I hold to: no testing in production; before deleting anything in
production, show who each row belongs to; and when a batch job reports success,
verify the effect, never the report.

---

## Stack

| | |
|---|---|
| **Languages** | TypeScript · JavaScript · Python |
| **Backend** | NestJS · Node.js · Express · REST · SSE · WebSockets |
| **Frontend** | Next.js · React · Tailwind CSS |
| **Data** | PostgreSQL · pgvector · MongoDB · Redis |
| **AI / LLM** | RAG pipelines · embeddings · vector search · evaluation harnesses · LangChain · Claude / OpenAI / Groq / Gemini |
| **Security** | JWT · OAuth2 · RBAC · multi-tenant isolation · rate limiting · OWASP |
| **Infrastructure** | Docker · GitHub Actions · Railway · Vercel · AWS S3 · MongoDB Atlas |
| **Blockchain** | Ethereum · BSC · Solana · TRON · WalletConnect |

---

## Before this

Five years at **Citar Tech** (2021–2025) building Web3 products: multi-chain
payment engines, DEX routing across Ethereum, BSC, Solana and TRON, and the API
security work that comes with moving other people's money.

---

<p align="center">
  <strong>Available for backend, platform and AI engineering work</strong><br>
  Brazil · LATAM · International &nbsp;|&nbsp; 🇪🇸 ES · 🇧🇷 PT · 🇬🇧 EN
</p>
