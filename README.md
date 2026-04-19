# Tamil Nadu Election 2026 — Fiscal Audit

An independent, non-partisan citizen analysis of Tamil Nadu's 2026 state election manifestos, measured against the state's actual fiscal capacity.

**Live site → [https://appfuntopia.github.io/TNaudit](https://appfuntopia.github.io/TNaudit)**

---

## What This Is

Every election cycle, Tamil Nadu parties announce promises worth tens of thousands of crores. This tool asks a simple question:

> **Can the state actually afford this — and what happens to public debt if it tries?**

This is not a political opinion site. It does not endorse or oppose any party. It applies the same methodology to every party equally.

---

## What It Does

- **Debt Meter** — shows how much Tamil Nadu may need to borrow in Year 1 and over 5 years if selected promises are implemented, benchmarked against the FRBM Act 3% deficit limit
- **Party vs Party** — compare any two parties promise-by-promise, category by category
- **Key Promises** — detailed cost breakdown of each major promise with fiscal impact rating
- **Revenue Offset Toggles** — pre-defined revenue scenarios (TASMAC, GST compliance, GIM investments) showing how income measures could offset spending
- **Why It Matters** — plain-language explanation of Tamil Nadu's current fiscal position
- **Bilingual** — full English and Tamil interface

---

## Fiscal Methodology

All cost estimates are approximations derived from publicly available data. They are **not** official government figures.

| Constant | Value | Source |
|----------|-------|--------|
| Revenue (FY25-26) | ₹3,32,000 Cr | TN Budget 2025-26 |
| Total Expenditure | ₹4,39,000 Cr | TN Budget 2025-26 |
| Current Debt Stock | ₹9,52,000 Cr | CAG / RBI |
| GSDP (FY25-26) | ₹35,67,000 Cr | Directorate of Economics & Statistics |
| Baseline Deficit | ₹1,07,000 Cr | TN Budget 2025-26 |
| FRBM Legal Limit | 3% of GSDP | FRBM Act 2003 |

Cost estimates use per-beneficiary unit costs scaled to Tamil Nadu's eligible population, cross-referenced against comparable scheme costs from other states and CAG audit findings.

---

## Data Sources

- TN Budget 2025-26 (Revenue & Expenditure statements)
- CAG Report on State Finances of Tamil Nadu (2023-24)
- RBI Handbook of Statistics on Indian States
- RBI State Finances — A Study of Budgets 2024-25
- PRS India — Tamil Nadu Budget Analysis 2025-26
- Official party election manifestos (publicly released)
- OpenCity.in — Tamil Nadu 2026 Manifesto Dataset

Full source list with links available in the **Sources** tab of the live site.

---

## AI & SGI Transparency Declaration

*Information Technology Rules 2021 (Amendment February 2026) — SGI Compliance*

Portions of this analysis were produced with AI assistance (Synthetically Generated Information — SGI under IT Rules 2021, Amendment February 2026), including:

- Tamil translations of party manifesto summaries
- Narrative summaries and plain-language explanations
- Fiscal impact estimation methodology design
- Data organisation and cross-referencing assistance

The underlying fiscal data is drawn from public sources listed above. Not every figure has been independently verified by a human — users are encouraged to check figures directly via the source links provided in the site.

This content is not intended to impersonate any individual, misrepresent real-world events, or constitute electoral misinformation.
*— Compliant with Rule 3(1)(b)(vii) of the IT Rules 2021 as amended February 2026.*

---

## Legal Disclaimer

- This website is an **independent citizen analysis**. It is not affiliated with any political party, government body, election commission, or media organisation.
- All figures shown are **estimated fiscal impacts** — approximations derived from publicly available data. They should not be read as actual, audited, or official costs.
- Estimated fiscal impacts will vary based on implementation details, eligibility criteria, benefit levels, and macroeconomic conditions.
- This site does **not** endorse or oppose any political party or candidate.
- Nothing on this site constitutes legal, financial, or electoral advice.
- This analysis is published in good faith for the purpose of **voter education and public interest**.

---

## Tech Stack

- [React 18](https://react.dev/) — UI
- [Vite](https://vitejs.dev/) — build tool
- No backend, no database, no tracking, no cookies
- Static site — fully client-side

---

## Run Locally

```bash
git clone https://github.com/AppFunTopia/TNaudit.git
cd TNaudit
npm install
npm run dev
```

Build for production:

```bash
npm run build
# output in dist/
```

---

## Contributing

Found a data error or a missing promise? Open an issue with a source link. All corrections are welcome — accuracy is the point.

---

## License

Content and analysis: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) — free to share and adapt with attribution, non-commercial, same license.

Code: [MIT](https://opensource.org/licenses/MIT)

---

*Published in the public interest. No individual or organisation takes personal responsibility for errors — see disclaimer above. Verify all figures independently before citing.*
