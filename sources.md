# Data sources — U.S. vs. Global EV Market 2025 Analysis

This dataset was compiled by hand from multiple primary industry reports, since no single
public dataset covers this comparison. Reconciling figures across sources — and flagging
where definitions differ — is treated as part of the analysis, not a gap in it.

## Primary sources

1. **Cox Automotive / Kelley Blue Book — Quarterly EV Sales Reports (2025)**
   - Q1 2025: https://www.coxautoinc.com/wp-content/uploads/2025/04/Q1-2025-Kelley-Blue-Book-EV-Sales-Report-04-11-25.pdf
   - Q2 2025: https://www.coxautoinc.com/insights-hub/q2-2025-ev-sales/
   - Q3 2025: https://www.coxautoinc.com/wp-content/uploads/2025/10/Q3-2025-Kelley-Blue-Book-EV-Sales-Report.pdf
   - Q4 2025 / full year: https://www.coxautoinc.com/insights/q4-2025-ev-sales-report-commentary/
   - Used for: all U.S. quarterly and annual EV sales figures

2. **IEA — Global EV Outlook 2025 and 2026**
   - https://www.iea.org/reports/global-ev-outlook-2025
   - https://www.iea.org/reports/global-ev-outlook-2026
   - Used for: global totals, China and Europe annual figures, EV share of total car sales

3. **Benchmark Mineral Intelligence — Global EV sales 2025**
   - https://source.benchmarkminerals.com/article/global-ev-sales-reach-20-7-million-units-in-2025-growing-by-20
   - Used for: global 2025 total (20.7M units) and monthly tracking through the year

4. **China Association of Automobile Manufacturers (CAAM)**
   - Cited via industry press (Electrek, SQ Magazine EV statistics roundup)
   - Used for: China's broader "NEV" (New Energy Vehicle) figure, which differs from IEA's
     narrower "electric car" definition — see note below

5. **ICCT — Global EV Market Monitor for Light-Duty Vehicles, 2025**
   - https://theicct.org/publication/global-ev-market-monitor-for-ldvs-2025/
   - Used for: regional market share detail, automaker-level share in the U.S. market

6. **U.S. EIA — "Today in Energy"**
   - https://www.eia.gov/todayinenergy/detail.php?id=67144
   - Used for: U.S. monthly BEV share context around the tax credit expiration

## Known data discrepancy — flagged, not hidden

China's 2025 EV figure appears two ways depending on the source:
- **IEA ("electric cars")**: ~12.8 million units — counts BEV + PHEV passenger cars only
- **CAAM ("NEV")**: ~16.49 million units — a broader category that includes more vehicle types

For any chart or headline stat, pick one definition and state it explicitly in the chart
footnote or dashboard subtitle. Mixing the two without flagging it would make the China
number look inconsistent with itself across different slides — worth calling out directly
in the write-up as a data-quality note; recruiters notice when analysts catch this kind of
thing rather than gloss over it.

## Notes on the tax-credit story (the core narrative)

Two U.S. federal EV tax credits — the New Clean Vehicle Credit and the Qualified Commercial
Clean Vehicle Credit — expired on September 30, 2025. This is the single policy event that
explains almost the entire U.S. quarterly pattern: a Q3 buying rush (record 438,487 units,
10.5% share) followed by a Q4 collapse (234,171 units, down 36% YoY). This date should be
annotated directly on any quarterly trend chart.
