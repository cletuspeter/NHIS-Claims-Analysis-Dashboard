# NHIS Claims Analysis Dashboard
### Tools: Python · MySQL · Power BI · Excel
### Timeline: 1 Week | Domain: Healthcare Analytics · Nigeria

## The Problem
Nigerian HMOs and hospital administrators struggle to understand why claims are being rejected, how long payments are taking, and where fraud is concentrated. Without visibility into these patterns, revenue leaks silently — month after month — with no clear path to recovery.
## What I Built
A five-page interactive Power BI dashboard analysing 3,000 NHIS health insurance claims across 13 Nigerian hospital providers and 5 HMOs. The dashboard tracks claim approval performance, rejection root causes, turnaround time efficiency, fraud signals, and geographic distribution — giving decision-makers a single view of their entire claims operation.

## Key Findings
The overall approval rate stands at 60.03% — meaning nearly 4 in every 10 claims submitted goes unpaid
Total revenue leakage reached ₦372,865,250 — representing 49% of all money claimed, with an average monthly loss of ₦31,072,104
Incomplete Documentation was the single largest driver of rejections at 32.56% — an operational failure, not a clinical one
AXA Mansard Health recorded the highest HMO rejection rate at 33.33%, while Reddington Hospital Lagos led provider-level rejections at 36.59%
470 claims — 15.67% of the dataset — fell into the Critical turnaround band, taking over 60 days to resolve. Clearline HMO recorded the slowest average processing time
153 claims (5.1%) were simultaneously high-value and fraud-flagged, representing a concentrated pool of financial risk requiring immediate investigation
Lagos University Teaching Hospital recorded the most fraud signals with 28 flagged claims across the period
Abuja generated the highest claim volume at ₦244,974,965, while Oyo State recorded the highest rejection rate at 33.04%

## The Business Impact
If Incomplete Documentation rejections alone were reduced by 60% through a structured pre-submission checklist — a zero-cost operational fix — the system would recover an estimated ₦7.2M per month in previously lost revenue. Addressing all five top rejection categories simultaneously could push the approval rate from 60% toward 75%, recovering over ₦18M monthly.

## Technical Process
Dataset was synthetically generated in Python using domain-accurate parameters, cleaned and validated across 9 quality checks in Jupyter Notebook, loaded into MySQL for KPI query analysis, and visualised in a five-page Power BI dashboard with 18 DAX measures, dynamic slicers, conditional formatting, and page-level navigation.
