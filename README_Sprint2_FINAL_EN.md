
# Sprint 2 – Segmentation & Time Trends

This repository presents the final, reviewer-free, English version of the Sprint 2 project.

## Sections (as in the notebook)
1. Introduction
2. Data Overview
3. Data Cleaning
4. Segmentation
5. Time Trends
6. Cohorts & Retention
7. Insights & Recommendations

## What this project does
- Segments customers (RFM or k-means) and labels them for business interpretation.
- Computes weekly/monthly aggregates and moving averages to highlight seasonality.
- Builds first-purchase cohorts to measure retention and repeat rates.
- Delivers actionable recommendations per segment (message, offer, channel, timing).

## How to run
```bash
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab  # or jupyter notebook
```

## Deliverables
- Clean notebook in English (no reviewer comments).
- Screenshots of main visuals (place in `reports/figures/`).
- One-pager summary: Problem → Approach → Insights → Actions.

**License:** MIT
