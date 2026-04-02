# SafeNest Advisory

### Hyderabad's first independent buyer-side real estate advisory.

> We represent buyers — never builders. Every report, every score, every recommendation exists to protect the buyer.

---

## What is SafeNest?

SafeNest is an independent real estate advisory firm based in Hyderabad, focused exclusively on West Hyderabad residential micro-markets — Kollur, Tellapur, Mokila, Kokapet, Narsingi, Manikonda, Patancheru, Gopanpally, Bachupally, and surrounding ORR corridors.

**We are not brokers. We are not builder representatives.**

Our revenue comes from advisory fees paid by buyers — not commissions paid by developers. This independence is the foundation of every output we produce.

---

## The Problem We Solve

A buyer in Hyderabad today walks into one of the fastest-moving real estate markets in India with almost no independent intelligence. Every channel partner, every broker, every sales office represents the builder. The buyer is alone.

SafeNest exists to change that. We give buyers the same quality of due diligence that institutional investors apply — applied to individual residential purchases in West Hyderabad.

---

## How It Works

Every project SafeNest analyses goes through a structured due diligence process across 8 parameters:

| Parameter | Weight |
|---|---|
| Legal & Title | 18% |
| Construction Progress | 18% |
| Developer Track Record | 15% |
| Location Quality | 15% |
| Product Quality | 12% |
| Escrow & Financial Structure | 10% |
| JV Compliance | 10% |
| Demand Signal | 2% |

This produces a **SafeNest Score** out of 10, a **Credit Rating** (AAA to B), and a **Verdict** (Highly Favorable / Favorable / Conditional / Unfavorable).

---

## The SafeNest System — What This Repository Contains

This repository is the operational backbone of SafeNest Advisory. It contains the complete methodology, field specifications, scoring architecture, and prompt system that powers every client deliverable.

```
safenest-advisory/
│
├── schema/
│   └── SafeNest_Schema_v2.3_Amendment.docx
│       Complete field-level schema specification. Covers all
│       tables, fields, formulas, views, weights, and ratings.
│       Current version: v2.3 (April 2026)
│
├── prompts/
│   ├── SafeNest_DataInput_Prompt_v2.3.docx
│   │   Master AI prompt for due diligence data extraction
│   │   and scoring from project documents.
│   │
│   ├── SafeNest_Buyer_Report_Prompt.docx
│   │   Generates the full buyer-facing Due Diligence Report
│   │   (CRISIL/Moody's quality, 13 sections).
│   │
│   ├── SafeNest_Advisor_Report1_Prompt.docx
│   │   Generates the Advisor Sales Brief — project-specific,
│   │   advisor-facing, with negotiation intelligence.
│   │
│   └── SafeNest_Advisor_Report2_Prompt.docx
│       Generates the 3-project comparison report for buyer
│       meetings. No ranking — all 3 presented as equals.
│
├── grid/
│   └── SafeNest_DataInput_Grid_v2.3.docx
│       Airtable implementation reference. Every field with
│       type, sequence, entry guidance, and formula syntax.
│
└── reports/
    ├── SafeNest_Advisory_Dashboard.html
    └── SafeNest_Buyer_Report.html
        Live HTML deliverables — buyer report and advisor
        dashboard rendered for client presentation.
```

---

## Deliverables

SafeNest produces three standard deliverables for every project engagement:

**1. Buyer Due Diligence Report**
Full 13-section report covering legal title, RERA compliance, construction stage, developer track record, escrow structure, risk assessment, and buyer advisory. Shared directly with the buyer. CRISIL/Moody's report quality.

**2. Advisor Report 1 — Project Brief**
Advisor-facing HTML report with SafeNest Score, location story, negotiation intelligence, buyer fit cards, and opening scripts. Confidential — not for client distribution.

**3. Advisor Report 2 — 3-Project Comparison**
Side-by-side comparison of 3 SafeNest-selected projects for a specific buyer's profile. Includes full parameter comparison table, per-unit metrics with belt context, and recommendation paragraphs. Presented at the buyer meeting.

---

## Technology Stack

| Layer | Tool |
|---|---|
| Database | Airtable (Projects table — 96 fields, 6 views) |
| Intelligence | Claude (Anthropic) — data extraction, scoring, report generation |
| Automation | Gemini |
| CRM | Streak |
| Deliverables | HTML (WhatsApp / browser) |

---

## Geographic Focus

**West Hyderabad ORR Corridor**

Kollur · Tellapur · Mokila · Kokapet · Narsingi · Manikonda · Patancheru · Gopanpally · Bachupally · Adibatla · Osman Nagar

---

## Schema Version

Current: **v2.3** — April 2026
Previous: v2.2 (March 2026) · v2.1 · v2.0

Full change history documented in `schema/SafeNest_Schema_v2.3_Amendment.docx`

---

## Contact

**Ameer · Founder & Director, SafeNest Advisory**
ameer.automation@gmail.com

*SafeNest Advisory is a RERA-registered independent buyer-side advisory firm. We do not accept commissions from developers. Title verification and legal opinion remain the buyer's responsibility through their independent advocate.*

---

*Confidential — This repository contains proprietary SafeNest methodology. Not for redistribution.*
