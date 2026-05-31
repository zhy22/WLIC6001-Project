# ANU Transnational Education (TNE) Pivot
---
> *"Being relatively smaller than other leading Australian universities provides a human-scale environment and a strong sense of community. However, this can work against us under some rankings criteria that prioritise scale."*
> — Australian National University, "Rankings in focus" (2024)

The whole argument of this analysis is that the rankings criteria are not the only thing being prioritised by scale — and that a structured TNE programme is the cleanest path to scaling internationally without consuming a single NOSC place.

---

<img width="2669" height="1396" alt="image" src="https://github.com/user-attachments/assets/e5888f54-3764-425b-942a-f057e1706fc9" />

> A data-driven consulting case study examining whether the **Australian National University (ANU)** should expand into transnational education (TNE) — and how — to address its declining international student revenue under Australia's NOSC cap regime.

[![Made with Python](https://img.shields.io/badge/Made%20with-Python%203.12-blue?logo=python)](https://www.python.org/)
[![Data: DoE](https://img.shields.io/badge/Data-Australian%20Dept%20of%20Education-darkblue)](https://www.education.gov.au/higher-education-statistics)
[![Status: Complete](https://img.shields.io/badge/Status-Complete-success)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## Table of contents

- [The brief](#the-brief)
- [Key findings](#key-findings)
- [Selected visualisations](#selected-visualisations)
- [Repository structure](#repository-structure)
- [Data sources](#data-sources)
- [Methodology](#methodology)
- [Reproducing the analysis](#reproducing-the-analysis)
- [Output deliverables](#output-deliverables)
- [Limitations](#limitations)
- [Acknowledgments](#acknowledgments)

---

## The brief

> *How could ANU recruit and diversify its future student cohorts — both domestically and internationally — amid shifting political and economic conditions and increasing global competition?*

This repository contains the data, code, and reports for a multi-week strategic analysis of ANU's competitive position. The work moves from broad industry context (global, Australian, and South Asian higher education trends) through ranking diagnostics and culminates in a deep-dive on transnational education as ANU's most viable offshore growth channel.

The central question this analysis answers: **given that ANU has reached only 76% of its 2025 NOSC allocation — generating an A$46 million revenue shortfall — and that the NOSC cap structurally constrains onshore growth, what offshore strategy can both replace lost revenue and address the underlying ranking and competitive challenges?**

---

## Key findings

1. **ANU is the only Go8 university that shrank** between 2020 and 2024 (−5.7%), while UWA (closest size comparator) grew 21.1% and UNSW grew 30.0%.
2. **ANU has the smallest overseas student EFTSL of any Go8** at 7,086 in 2024 — roughly one-fifth of Monash's 33,869.
3. **TNE bypasses the NOSC cap entirely.** The Australian Government has confirmed TNE students are exempt from provider NOSC allocations and receive Priority 1 visa status.
4. **Sector overseas demand is growing fastest in fields where ANU is small** — Education +59.8%, IT +21.7%, Health +13.1% year-on-year (2023→2024).
5. **A combined India + Vietnam TNE programme could generate 2,000–2,500 students and A$30–50M in NOSC-exempt revenue by Year 5**, sufficient to offset ANU's current A$46M NOSC shortfall.
6. **ANU is the only Go8 with no announced TNE entry** in India. UWA, Deakin, Wollongong, WSU, and Victoria are all approved or operational — creating a 12–18 month first-mover gap to close.

---

## Selected visualisations

### ANU has shrunk while most Go8 peers have grown

<img width="1635" height="972" alt="image" src="https://github.com/user-attachments/assets/fcd63a11-482e-474a-84ab-fd9a2eb6d2e2" />


ANU's total enrolment fell from 24,336 (2020) to 22,939 (2024) — a −5.7% contraction — while every other Go8 university grew. UNSW added the most absolute volume (+19,000 students), and even UWA, ANU's closest size comparator, expanded by 21.1%. ANU's QS overall score of 87.4 in 2026 was its highest in six years, yet its rank fell from #19 (2016) to #32 (2026) because peer institutions improved faster.

---

### UWA has overtaken ANU and moved on TNE first

<img width="1943" height="827" alt="image" src="https://github.com/user-attachments/assets/8a3653f3-4f34-4022-bc9e-9cd8ba24e413" />

UWA started 2020 only 81 students ahead of ANU. By 2024 the gap was **6,630 students**. UWA received UGC approval for branch campuses in Mumbai and Chennai in June 2025, scheduled to open in 2026. ANU has not yet announced a TNE entry — quantifying a 12–18 month Go8 first-mover gap.

---

### ANU's strongest fields are precisely where TNE demand is concentrated
ANU's 2024 enrolment by Broad Field of Education reveals a strategic alignment: 42.1% of students are in Society & Culture (ANU's policy/IR strength → differentiated TNE niche), and 22.9% in Management & Commerce (top onshore demand from India/Vietnam → mainstream TNE alignment). The combination supports both a defensible niche programme strategy and capacity for high-volume markets.
<img width="2523" height="1397" alt="image" src="https://github.com/user-attachments/assets/0ec2c976-2506-4a10-b59c-da4ac95b5d08" />

---

### ANU has the smallest overseas student EFTSL of any Go8
Two convergent findings on one page. **Left:** ANU's overseas EFTSL of 7,086 is the smallest of any Go8 — below UWA's 7,685 and roughly one-fifth of Monash's 33,869. **Right:** Sector-wide overseas demand is growing fastest in Education (+59.8%), Information Technology (+21.7%), and Health (+13.1%) — fields where ANU has only 0, 1,845, and 809 students respectively. The strategic mismatch is unambiguous.
<img width="1635" height="972" alt="image" src="https://github.com/user-attachments/assets/a7fe100d-87d2-49dd-b640-8bf3ec561820" />

---

### TNE could restore lost enrolment and exceed it by 2030
<img width="2086" height="1198" alt="image" src="https://github.com/user-attachments/assets/0e518ee8-1b0b-42c4-a53e-7f76f6e4ee60" />


ANU's actual enrolment trajectory (2020–2024) joined to two projection scenarios. Without TNE, ANU stays flat at 22,939. With a combined Vietnam twinning + India branch campus programme, ANU could add 2,000–2,500 students by Year 5, generating ≈A$30–50M in NOSC-exempt revenue — sufficient to offset the current A$46M shortfall and add 9–11% to total enrolments.
## Competitor analysis: ANU vs Go8 and non-Go8 comparators

A single four-panel view consolidates the strategic position of ANU against its Go8 peers and the offshore-active comparator set. The chart compresses four otherwise separate findings into one paste-ready figure for the report and slide deck.

<img width="1316" height="902" alt="image" src="https://github.com/user-attachments/assets/953f80f0-4ddc-419d-9832-0f5489ccd4cb" />


**Panel A — Overseas EFTSL: ANU is the smallest in the Go8.** Even held against just the top of the Go8, ANU's 7,086 overseas student EFTSL in 2024 is roughly 21% of Monash's 33,869. This is not a function of total institutional scale (ANU and UWA are similarly sized overall) but a structural under-investment in the international channel. The implication: ANU does not need a new market to grow — it needs to use the international channel that peers have already proven.

**Panel B — Onshore enrolment trajectory: ANU is the only Go8 contracting.** Between 2020 and 2024, ANU's total enrolment fell 5.7% (from 24,336 to 22,939), while UWA — the closest size comparator — grew 21.1%. Every other Go8 grew in the same window. ANU is therefore not facing a sector-wide demographic headwind; it is losing share within a growing peer group.

**Panel C — Offshore footprint: ANU is the only Go8 with zero TNE delivery.** Monash (Malaysia: 10,000+ students from 85 countries; new KL campus for 22,500 students, announced at RM2.8bn) and RMIT (Vietnam: ~23,000 students at a standalone branch) anchor the upper end. Deakin's GIFT City India campus is operational. Wollongong, WSU, Victoria, and UWA hold approved or operational Indian campuses. ANU is alone in this peer set with no announced TNE entry — quantifying a 12–18 month first-mover gap to close.

**Panel D — Demand growth concentrated in fields where ANU is sub-scale.** Sector-wide overseas demand grew 59.8% in Education and 21.7% in IT between 2023 and 2024. ANU has only 1,845 IT students (7.4% of its enrolment) and minimal Education enrolment. The corollary — shown in the inset — is that ANU's QS-leading subjects (Philosophy #8, Anthropics #9, Archaeology #10, Politics #11, Development Studies #14) are policy, governance, and humanities fields that no other Australian TNE provider currently serves. The strategic option is therefore not to compete head-to-head on the high-growth STEM fields where peers have first-mover advantage, but to build TNE programmes around the differentiated policy/governance niche where ANU is world-leading and the competitive set is empty.

Read together, the four panels make the case for TNE entry without further inference: ANU has the smallest international channel of any Go8, the only declining domestic enrolment, the only empty offshore footprint, and a subject-mix that is simultaneously sub-scale in the highest-growth fields and uniquely differentiated in the highest-margin niche. TNE is the channel that resolves all four positions at once.

---

*Sources: Australian Department of Education 2024 (Higher Education Student Statistics, Section 7, Tables 7.2 and 7.5; perturbed pivot 2020–2024); PM Albanese 2025 Monash KL launch; QS World University Rankings by Subject 2025; institutional disclosures (Deakin, UWA, Wollongong, WSU, Victoria, RMIT).*
<img width="1701" height="2961" alt="image" src="https://github.com/user-attachments/assets/b6da65bc-f87c-4c0c-abae-3b5dc85ad00a" />

---

## Repository structure

```
anu-tne-analysis/
├── README.md                                # This file
├── LICENSE                                  # MIT
│
├── data/
│   ├── Perturbed_Student_Enrolments_Pivot_Table_2024.xlsx
│   │   └── Source: Australian Dept of Education (institution × year)
│   └── 2024_Section7_Overseas_Students.xlsx
│       └── Source: Australian Dept of Education (overseas EFTSL by inst.)
│
├── notebooks/
│   ├── 01_data_loading_and_cleaning.ipynb
│   ├── 02_enrolment_trend_analysis.ipynb
│   ├── 03_overseas_eftsl_benchmarking.ipynb
│   └── 04_tne_market_sizing.ipynb
│
├── src/
│   ├── plots/
│   │   ├── plot1_go8_trajectory.py          # ANU vs Go8 lines
│   │   ├── plot2_anu_vs_uwa.py              # head-to-head
│   │   ├── plot3_field_of_education.py      # ANU FOE mix
│   │   ├── plot4_top10_enrolment.py         # scale comparison
│   │   ├── plot5_growth_rates.py            # winners and losers
│   │   ├── plot6_tne_counterfactual.py      # projection
│   │   └── plot7_overseas_eftsl.py          # combined panel
│   └── style.py                             # shared palette + rcParams
│
├── outputs/
│   ├── *.png                                # all generated plots (150 DPI)
│   └── reports/
│       ├── 01_HE_Data_Sources_Reference.docx
│       ├── 02_ANU_Rankings_HE_Trends_Report.html
│       ├── 03_Strategic_Proposal.html
│       ├── 04_Research_Framework_Sections.docx
│       ├── 05_TNE_Deep_Dive_Framework.docx
│       ├── 06_TNE_Data_Collection_Analysis.docx
│       └── 07_TNE_Section_Final.docx
│
└── requirements.txt
```

---

## Data sources

| # | Source | Coverage | Use in this project |
|---|--------|----------|---------------------|
| 1 | **Australian Department of Education** — Higher Education Statistics Collection 2024 (perturbed pivot) | All Australian HEIs, 2020–2024 | Plots 1, 2, 3, 4, 5, 6 — enrolment trajectories, growth rates, field-of-education mix |
| 2 | **Australian Department of Education** — Section 7 Overseas Students 2024 | All Australian HEIs, 2024 | Plot 7 — overseas EFTSL, sector demand growth by field |
| 3 | **Department of Education** — International Student Monthly Summary (PRISMS) | Monthly YTD, 2002–present | Source country shares, commencement trends |
| 4 | **AISHE** (Indian Ministry of Education) — 2021–22 | All Indian HEIs | India market sizing: 43.3M students, GER 28.4% |
| 5 | **UNESCO Institute for Statistics** — Outbound Mobility | 200+ countries, 1970–present | Cross-country mobility baseline |
| 6 | **British Council / HESA AOR** — UK TNE statistics | UK universities, 2020/21–2024/25 | UK comparator: 663,970 TNE students at +7.8% CAGR |
| 7 | **QS World University Rankings** 2016–2026 + Subject Rankings 2025 | Global | Ranking decomposition, subject-level analysis |
| 8 | **Times Higher Education** World University Rankings 2026 | Global | Ranking sub-indicator analysis |
| 9 | **HolonIQ 2025 Global Education Outlook** | Global | Market sizing: US$10T by 2030 |
| 10 | **Deloitte 2025 / 2026 Higher Education Trends** | Global, US-focused | US enrolment decline (−17% intl, fall 2025) |
| 11 | **Institutional disclosures** — Monash, Deakin, UWA, Wollongong, WSU | TNE benchmarks | Branch campus and twinning model comparisons |
| 12 | **The Koala News** — ANU Roadmap reporting | ANU-specific | NOSC shortfall (76%, A$46M), Foundation College, UC College ELICOS pilot |

A complete reference list with 35+ citations is included in the final report (`outputs/reports/07_TNE_Section_Final.docx`).

---

## Methodology

The analysis follows a four-stage approach:

1. **Industry framing.** Global, Australian, and South Asian higher education trends are mapped against the data sources that quantify them (UNESCO UIS, OECD EAG, AISHE, PRISMS).
2. **Diagnostic ranking analysis.** ANU's QS, THE, US News, ARWU, and CWUR rankings are decomposed to sub-indicator and subject level to identify where ANU is losing ground and where it is differentiated.
3. **Comparative benchmarking.** ANU is benchmarked against three Australian TNE archetypes (Monash Malaysia branch campus; Deakin GIFT City India campus; WSU–UEH Vietnam twinning partnership) and against UWA as the closest size comparator.
4. **TNE deep dive.** Market sizing (India + Vietnam), resource requirements, financial projections, and a counterfactual scenario test against ANU's NOSC shortfall.

### Plot styling

All plots share a consistent visual language to support narrative flow across the report deliverables:

```python
# Font & colour setup
NAVY      = "#1C2D5E"   # primary brand navy
NAVY_MID  = "#2E4478"   # secondary navy
NAVY_LITE = "#7B8EC8"   # accent / comparator colour
NAVY_PALE = "#D6DCF0"   # background fill / peer bars
GOLD      = "#C9A227"   # ANU highlight ONLY
TEXT      = "#1A1A2E"   # body text
GRID      = "#C8CDD8"   # subtle gridlines

BASE = 12               # 12 pt throughout
FONT = "TeX Gyre Termes"  # Times-equivalent serif
```

ANU is consistently rendered in **gold** across every chart, peers in graduated **navy** shades. This single visual rule makes "where is ANU?" a one-second cognitive task in every figure.

---

## Reproducing the analysis

### Requirements

```bash
python >= 3.10
pandas >= 2.0
matplotlib >= 3.7
openpyxl >= 3.1
numpy >= 1.24
```

Install:

```bash
pip install -r requirements.txt
```

### Running

```bash
# Place data files in ./data/
git clone https://github.com/<your-org>/anu-tne-analysis.git
cd anu-tne-analysis

# Generate all plots
python -m src.plots.plot1_go8_trajectory
python -m src.plots.plot2_anu_vs_uwa
# ... or run all:
make plots

# Outputs land in ./outputs/
```

The plots regenerate deterministically. PRISMS-based numbers will refresh as the Department of Education publishes new monthly data; re-run after replacing the source XLSX.

---

## Limitations

- **Perturbed source data.** The Department of Education's pivot table applies input perturbation for disclosure control. Cell counts are within ±2% of true values for institution-year cells, but field-of-education breakdowns may have larger relative noise for small subgroups.
- **Reporting lags.** Australian offshore education statistics lag by 12–18 months. The most recent comprehensive data point is 2022 (Section 7 covers up to 2024). Some 2025 figures are partial estimates from PRISMS.
- **TNE definition variation.** Different jurisdictions and reporting bodies define TNE differently. UK–Australia comparisons are indicative; the 1:5 vs 0.95:1 ratio comparison should be interpreted as directional.
- **Financial projections are estimates.** Setup costs and revenue per student are derived from public fee schedules and peer benchmarks (Monash Malaysia, Deakin GIFT City). Actual results will depend on programme mix, fee strategy, and operational execution.
- **Perturbed totals may not match published aggregates.** This is by design in the source data and noted in all chart captions.

---

## Acknowledgments

This analysis draws on the open data programmes of the **Australian Department of Education**, **UNESCO Institute for Statistics**, **OECD**, **British Council**, **Indian Ministry of Education (AISHE)**, **QS Quacquarelli Symonds**, and **Times Higher Education**. Strategic context was informed by the work of **Andrew Norton** (ANU Migration Hub), **Future Campus**, **ICEF Monitor**, **HolonIQ**, and **Deloitte Insights**.

ANU branding colours and typographic conventions are used here for illustrative analytical purposes only. This is an independent analysis and not an official ANU publication.

---

## License

Released under the [MIT License](LICENSE). Data files retain their original licensing terms — see each source for details.

---


