# GrowthIQ — Project Context
> This file is the canonical reference for the GrowthIQ / Growth Firm engagement.
> Update this file at the end of every working session, alongside Notion.
> Read this at the start of any new Claude session (chat, CoWork, or Claude Code).

---

## Last Updated
21 May 2026

---

## The Entities

### GrowthIQ
- B-BBEE Enterprise & Supplier Development (ESD) compliance platform
- **Jointly owned by SeokaneInc and Growth Firm** — not registered as a separate company yet
- Domain: `growthiq.co.za` (registered, owned by SeokaneInc)
- Live portal: `portal.growthiq.co.za`
- 14 active clients on the portal
- Built and currently hosted by **NetGen (Pty) Ltd** — SeokaneInc pays R1,380/month
- SeokaneInc holds the source code — NetGen exit is viable
- NetGen has proposed a feature update — SeokaneInc has paused them pending this engagement

### Growth Firm
- Professional services firm: accounting, tax, payroll, legal
- Website: `growthfirm.co.za` (WordPress/Elementor, hosted at Afrihost)
- Supporting entity in this engagement — runs alongside GrowthIQ, not after it

### SeokaneInc
- Holding entity — primary counterparty for contracts with Maru
- Director: City Seokane
- Has a target list of 80–100 corporate ESD prospects in Excel format

---

## Maru's Role

Three pillars:
1. **Infrastructure** — migrate portal off NetGen, manage all digital infrastructure on retainer
2. **Product** — GrowthIQ brand, portal remediation, Growth Firm website rebuild, AI integration layer
3. **Growth** — design and execute corporate outreach against the 80–100 target list

Partnership model, not vendor. Maru has performance upside tied to new GrowthIQ corporate contracts.

---

## Portal Tech Stack
- **Status: UNCONFIRMED** — to be established during Phase 1 source code review
- Not Node.js (confirmed by client)
- Likely PHP-based given the portal's architecture and NetGen's profile — but do not assume until the codebase is reviewed
- Sentry monitoring is installed but broken (both required files returning errors)

---

## Phase Status

| Phase | Scope | Status | Fee Range |
|-------|-------|--------|-----------|
| Phase 1 | Infrastructure migration — exit NetGen, Maru-managed hosting | **Not started — awaiting sign-off** | R8,000–R15,000 |
| Phase 2 | GrowthIQ brand spin-out + portal UX remediation | Not started | R35,000–R55,000 |
| Growth Firm rebuild | Next.js website rebuild on Vercel | Not started | R25,000–R35,000 |
| Phase 3 | AI integration layer | Not started | R45,000–R75,000 |

**Total indicative project investment:** R113,000–R180,000 across all phases over 4–6 months.

**Monthly retainer** (begins Phase 1 completion): R4,500–R6,500/mo
Covers: hosting, uptime monitoring, security patches, deployments, ongoing maintenance — both entities.

**Growth upside:** 10–15% revenue share on net new GrowthIQ corporate contracts originated through the outreach engine. Exact structure TBD before Phase 3.

**Payment terms:** 50% upfront, 50% on delivery per project phase. Retainer invoiced on the 1st.

---

## Open Items (as at 21 May 2026)

| # | Priority | Item |
|---|----------|------|
| 01 | Blocker | NetGen contract — confirm if active, get exit terms |
| 02 | Blocker | Source code review — confirm stack, completeness, deployability |
| 03 | Required | Corporate target list — get the Excel file |
| 04 | Required | Commercial framework — agree final fees and growth upside % |
| 05 | Planning | GrowthIQ company registration — confirm shareholding split between SeokaneInc and Growth Firm before Phase 2 |

---

## Key Deliverables (Framework Report)
Live at: https://maru-diagnostic-reports.vercel.app/clients/growth-firm/framework
Version: 1.0 — sent 20 May 2026, SeokaneInc name corrections applied 21 May 2026

## Diagnostic Report
Live at: https://maru-diagnostic-reports.vercel.app/clients/growth-firm
Version: 1.1 — delivered 15 May 2026

---

## Repo
GitHub: https://github.com/jimmy-motsei/maru-diagnostic-reports
Local: /Users/ramoloimotsei/code/maru-diagnostic-reports
Hosted: https://maru-diagnostic-reports.vercel.app
