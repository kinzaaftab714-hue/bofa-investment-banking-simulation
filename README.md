# Bank of America – Investment Banking Job Simulation

**M&A Valuation Analysis: Nintendo as a Strategic Acquisition Target for Webflix**

This repository documents an M&A advisory exercise completed as part of the **Bank of America Investment Banking Job Simulation** on Forage — evaluating a hypothetical acquisition of Nintendo Co., Ltd. by Webflix, Inc. (a fictional global streaming company modeled on real-world 2021 financial disclosures) from the perspective of a junior investment banking analyst.

---

## 📌 Deal Context

Webflix, a leading global streaming entertainment provider, is exploring inorganic growth opportunities to strengthen its content ecosystem and expand into new markets. Nintendo was identified as a compelling acquisition target due to its industry-leading gaming IP portfolio and strong footprint in the Asia-Pacific region.

The task: build a company profile of the target, construct a Discounted Cash Flow (DCF) valuation to estimate what Bank of America should recommend as a fair value range, and summarize the acquirer's own financial standing to assess deal feasibility.

---

## 🎯 Strategic Rationale for the Acquisition

- **Strengthen Gaming Capabilities** — Acquiring Nintendo would allow Webflix to immediately accelerate its internal video game content capabilities, deepening customer engagement and expanding its total addressable market.
- **Deepen Penetration in the APAC Region** — Nintendo generates approximately **24% of its total revenue from Japan alone**, giving Webflix a strategic foothold to strengthen its presence in the key Asia-Pacific market.

---

## 🎮 Target Company Profile: Nintendo Co., Ltd.

| Metric | Value |
|---|---|
| Headquarters | Kyoto, Japan |
| CEO | Shuntaro Furukawa |
| Employees | 6,500+ |
| Revenue | $13.6 billion |
| EBITDA | $5.4 billion |

Nintendo is one of the largest entertainment companies in the world, designing, manufacturing, and selling video game hardware and software, playing cards, and other toys across the handheld, home console, and mobile gaming markets. Over nearly 40 years, the company has driven major consumer electronics innovation — from the Game Boy and NES through to the Wii and Nintendo Switch — and its portfolio includes some of the most recognizable franchise assets in entertainment.

---

## 💰 Valuation: Discounted Cash Flow (DCF) Analysis

A 5-year unlevered free cash flow model was built to estimate Nintendo's intrinsic enterprise and equity value.

### Key Assumptions
| Assumption | Value |
|---|---|
| Base Year Revenue (2022E) | $13,600.0M |
| Revenue Growth Rate | 5% annually |
| EBITDA Margin | Expanding from ~40% to 42% by Year 5 |
| WACC (Discount Rate) | 8.5% |
| Terminal EBITDA Multiple | 12.0x |
| Corporate Tax Rate | 40% |

### Valuation Output
| Metric | Value |
|---|---|
| PV of 5-Year Unlevered FCF | $14,150.0M |
| PV of Terminal Value | $55,408.7M |
| **Implied Enterprise Value** | **$69,558.7M** |
| Plus: Cash | $9,200.0M |
| Less: Debt | ($50.0M) |
| **Implied Equity Value** | **$78,708.7M** |
| Shares Outstanding | 1,000M |
| **Implied Share Price** | **$78.71** |

### Sensitivity Analysis
A two-way sensitivity table was built flexing **WACC (7.0%–9.0%)** against **Terminal Multiple (11.0x–13.0x)**, producing an enterprise value range of **$62.9B–$78.1B** and an implied share price range of **$72.06–$87.23**.

**Conclusion:** Based on the DCF analysis and sensitivity range, Nintendo's fair valuation midpoint is estimated at approximately **$70B**, within a defensible range of **$57.9B–$82.3B**.

---

## 🏢 Acquirer Financial Summary: Webflix, Inc.

To assess whether Webflix is financially positioned to pursue an acquisition of this scale, a 3-year financial summary was built from Webflix's FY2021 Annual Report (Form 10-K).

| ($ in thousands) | FY2019 | FY2020 | FY2021 |
|---|---|---|---|
| Revenue | $20,156,447 | $24,996,056 | $29,697,844 |
| Gross Profit | $7,716,234 | $9,719,737 | $12,365,161 |
| Gross Margin | 38.3% | 38.9% | 41.6% |
| Operating Income | $2,604,254 | $4,585,289 | $6,194,509 |
| EBITDA | $2,707,833 | $4,700,999 | $6,402,921 |
| EBITDA Margin | 13.4% | 18.8% | 21.6% |
| Total Assets | $33,975,712 | $39,280,359 | $44,584,663 |
| Total Debt | $14,759,260 | $16,308,973 | $15,392,895 |
| Shareholder's Equity | $7,582,157 | $11,065,240 | $15,849,248 |
| Free Cash Flow | ($3,274,386) | $1,921,723 | ($158,894) |
| Total Debt / EBITDA | 5.45x | 3.47x | 2.40x |

### Key Observations
- Webflix's revenue grew **19% year-over-year in FY2021**, with EBITDA margin expanding from **13.4% (2019) to 21.6% (2021)** — reflecting improving operating leverage as the business scaled.
- **Leverage has meaningfully declined**, with Total Debt/EBITDA falling from 5.45x in 2019 to 2.40x in 2021, indicating growing balance sheet capacity to fund strategic M&A.
- However, **Free Cash Flow was negative in FY2021** (-$158,894K), driven primarily by continued heavy investment in content assets — a key consideration for how a Nintendo acquisition would be financed (cash/debt mix) without straining near-term liquidity.
- With **$6.0B in cash** and access to an undrawn **$1B revolving credit facility** as of FY2021, Webflix retains meaningful near-term financing flexibility despite negative free cash flow.

---

## 🛠️ Tools & Methods

- **Microsoft Excel** — Discounted cash flow modeling, sensitivity analysis (data tables), and financial statement summarization
- **Microsoft PowerPoint** — Target company profile and valuation summary deck, in standard investment banking pitch-book format
- Valuation approach: **Discounted Cash Flow (DCF)** with terminal value via exit multiple method, cross-checked with a WACC/terminal multiple sensitivity grid

---

## 📁 Repository Contents

| File | Description |
|---|---|
| `DCF_BofA_Final.xlsx` | Full 5-year unlevered DCF model for Nintendo, including sensitivity tables for enterprise value and implied share price |
| `Nintendo_Profile_Model_Final.pptx` | Two-slide investment banking-style deck: target company profile and DCF valuation summary |
| `Webflix_Financial_Summary_Final.xlsx` | 3-year historical financial summary of Webflix (the acquirer), built from its FY2021 Form 10-K |

---

## 💡 What This Project Demonstrates

- Building a **DCF valuation model from scratch** — including free cash flow projections, terminal value estimation, and WACC-based discounting
- Translating raw 10-K financial statement data into a clean, decision-ready **acquirer financial summary**
- Constructing a **sensitivity analysis** to stress-test valuation assumptions rather than relying on a single point estimate
- Framing a valuation output within a broader **M&A strategic narrative** — connecting the numbers to the business rationale for the deal

---

*Completed as part of the Bank of America Investment Banking Job Simulation via Forage. Webflix, Inc. is a fictional company for the purposes of this exercise, modeled on publicly available real-world streaming industry financial data.*
