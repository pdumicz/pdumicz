# Patryk Dumicz

**I build AI products and lead delivery in regulated, high-stakes environments.**

Head of PMO & Cybersecurity at [Securnite](https://securnite.com) · Ex-Robinhood TPM · CISSP (in progress) · Zurich 🇨🇭

---

I sit at the intersection of **product engineering** and **security/compliance leadership** — I ship AI-powered products end-to-end, and I run portfolios across GRC, offensive security, and enterprise delivery.

Before my current role, I built open-source developer tools at the Linux Foundation with Google and Mastercard, led strategic programs for Saudi Aramco, and co-founded and exited a conversational AI startup in London.

---

### What I'm building

<table>
<tr>
<td width="33%" valign="top">

#### 🔒 [evalfa.st](https://evalfa.st)
**AI security scanner with compliance evidence automation**

Built a security scanner from scratch that tests LLM endpoints against all 10 OWASP LLM Top 10 categories and generates audit-ready evidence mapped to SOC 2, ISO 27001, ISO 42001, DORA, NIS2, and FINMA controls.

**Scope:** Architecture, scanner engine, compliance control mapping (40+ controls across 7 frameworks), infrastructure, GTM.

`Next.js` · `Supabase` · `Python` · `Hetzner VPS` · `Docker` · `Vercel`

</td>
<td width="33%" valign="top">

#### 📦 [Fyord](https://getfyord.com)
**AI agent that turns emails into ERP orders — no re-typing**

Reads inbound B2B orders (PDFs, Excel, plain text), auto-matches customers and SKUs in Fortnox, drafts order lines for human approval, and autonomously chases customers for missing info. Currently onboarding pilot customer.

**Scope:** End-to-end — AI agent architecture, Fortnox API integration, Outlook mailbox ingestion, exception routing, customer-specific learning, EU-hosted infra.

`Next.js` · `Convex` · `Claude Agent SDK` · `Hetzner VPS` · `Docker` · `Clerk` · `Vercel`

</td>
<td width="33%" valign="top">

#### ⚡ [AutoKarp](https://autokarp.com)
**Karpathy's AutoResearch loop, delivered as SaaS**

Platform that provisions GPU infrastructure and orchestrates autonomous ML research loops — making iterative experimentation accessible to engineers who don't manage their own GPU clusters.

**Scope:** Platform architecture, RunPod GPU orchestration, containerized experiment pipelines, monitoring, user-facing dashboard.

`Next.js` · `Python` · `RunPod API` · `Hetzner VPS` · `Docker` · `Vercel`

</td>
</tr>
</table>

---

### Open source

#### 🛡️ [Secret Shuttle](https://github.com/pdumicz/secret-shuttle)
**Secure secret transport for AI coding agents — the model never sees the raw value.**

CLI tool that lets AI agents (Claude Code, Codex, Cursor) handle production secrets without exposing them to the model's context window. Uses Chrome CDP to capture secrets in "blind mode," encrypts them locally, and injects them into target fields — the agent only ever sees a reference handle and a SHA-256 fingerprint.

Built to solve a real problem I hit while using AI agents to configure production infrastructure: the secret has to move from Stripe to Vercel, but it should never pass through the LLM.

`TypeScript` · `Playwright CDP` · `Node.js` · Threat model & security docs included

---

### Other projects

**[RoxSkills](https://roxskills.app)** — AI-powered HYROX form coach. Analyzes workout video to score technique across 8 exercises with real-time coaching feedback. `React Native` · `Expo` · `Gemini API` · `RevenueCat`

**[AICompliancePulse](https://aicompliancepulse.com)** — Automated AI regulatory intelligence. Aggregates and summarizes compliance developments across EU AI Act, NIST, ISO, and industry frameworks. `Next.js` · `Convex` · `OpenAI API`

---

### Writing & thinking

<!-- Add LinkedIn article URL when ready -->
📝 **[Foundation Models vs. Agent Runtime: Where the real business opportunity lies](#)** — Long-form analysis of how foundational model companies are moving up-stack, how European companies are responding, and where the opportunities sit for incumbents, startups, and open-source projects.

---

### Background

| | |
|---|---|
| **Now** | Head of PMO & Cybersecurity Portfolio Manager — Securnite, Zurich. Built the PMO from zero. Own GRC, compliance, and offensive security portfolio across 3 countries. |
| **Previously** | TPM at Robinhood / Linux Foundation (open-source tools with Google, Mastercard, Lyft) · Lead Consultant at Saudi Aramco (strategic portfolio, world's largest company) · Co-founded & exited CRM Bot (conversational AI, London) |
| **Certs** | CISSP (in progress) · PSPO · SAFe · AgilePM · ITIL · ServiceNow |
| **Education** | BSc Computer Science — Polish-Japanese Academy of IT, Warsaw |

---

### Let's talk

I'm open to senior roles in **Zurich** — whether that's leading product engineering, running AI platform programs, or building at the intersection of security and AI.

📬 [dumiczpatryk@gmail.com](mailto:dumiczpatryk@gmail.com) · [LinkedIn](https://linkedin.com/in/pdumicz)
