# RBI vs. MAS: Inflation Targeting vs. Exchange-Rate Targeting

A comparative policy brief on how India's central bank (RBI, inflation targeting via the repo rate) and Singapore's (MAS, exchange-rate targeting via the S$NEER band) fought the same 2021–23 commodity shock.

**Author:** Kaheesha Ahmed (MSc Applied Economics, NUS)

## Research question
Why do two Asian economies with the same goal, price stability, use opposite instruments, and what did the 2021–23 shock show about the limits of each?

## Main findings
- RBI raised the repo rate six times (250 bp, May 2022 to Feb 2023). MAS tightened five times through the S$NEER band (Oct 2021 to Oct 2022) and stopped about four months before the RBI.
- Instrument choice tracks trade openness: trade was about 45% of GDP in India vs about 326% in Singapore (2023).
- Over 2021–23, food and beverages explain about 80% of the variance of India's headline inflation; MAS Core Inflation explains about 87% of Singapore's.

## Files
| File | What it is |
|---|---|
| `RBI_vs_MAS_Policy_Brief_Final.pdf` | The full brief |
| `RBI_MAS_Inflation_Decomposition(2) .xlsx` | Workbook with live formulas for the variance decomposition (sheets: Assumptions, Data, Decomposition) |
| `India Singapore Inflation Raw Data 2020 2026.xlsx` | Raw data as collected |
| `chart_india_cpi_repo.png`, `chart_singapore_cpi_sneer.png` | Figures used in the brief |

## Data sources
- MoSPI Consumer Price Index, All India combined, 2012=100 (headline, food and beverages, Consumer Food Price Index, fuel and light)
- SingStat Consumer Price Index and MAS Core Inflation (2024=100); MAS S$NEER weekly index
- RBI Monetary Policy Committee press releases; MAS Monetary Policy Statements
- World Bank World Development Indicators (trade % of GDP)

## Method
Year-on-year inflation is computed from index levels (India: MoSPI's published rates). The variance share of a component is Cov(component contribution, headline y/y) / Var(headline y/y) over Jan 2021 to Dec 2023 (36 months), computed in Excel with `COVARIANCE.S` and `VAR.S`. India's contributions use MoSPI 2012-base weights (food and beverages 45.86, fuel and light 6.84, other groups 47.30). Singapore's split is headline versus MAS Core Inflation; the residual is accommodation and private transport. The two splits are not like-for-like, because MAS core still includes food and energy. Shares describe co-movement, not causation.

## Data notes
- The analysis window is 2021–23. India rows for Oct 2024 to Feb 2025 in the raw file are inconsistent and are not used.
- Repo-rate entries for 2025 in the raw master sheet are not used in the analysis and contain errors.
- Singapore series are the rebased 2024=100 data, so y/y rates can differ from originally published figures by about 0.1 percentage point.
