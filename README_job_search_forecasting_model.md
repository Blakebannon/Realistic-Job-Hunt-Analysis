
# Realistic Job Search Forecasting Model

This project models a conservative job-search forecast for a candidate applying across:

- Data Analyst / Revenue Analytics roles
- Data Science / Applied Analytics roles
- AI / RAG / Agentic AI roles

The model intentionally avoids optimistic assumptions and accounts for:

- Low cold-application conversion rates
- High applicant competition
- Career-pivot penalty
- Resume/category fit differences
- Weekday vs weekend application volume
- Response lag
- Interview-process lag
- Offer negotiation lag
- Monte Carlo variance

## Core Modeling Idea

The notebook separates:

1. The date enough applications are submitted
2. The date an offer could realistically arrive

This matters because job offers usually do not arrive immediately after application volume milestones are reached.

## Key Outputs

The notebook generates:

- Candidate job-category fit scores
- Conservative application funnel assumptions
- Application volume needed for 25%, 50%, 70%, 80%, and 90% probability thresholds
- Calendar-based cumulative application projections
- Offer-probability-over-time charts
- Brutal cold-market sensitivity analysis
- Monte Carlo simulations for time-to-offer and application-number-to-offer
- CSV exports for further analysis

## Practical Interpretation

Under conservative assumptions, the model suggests:

- 250 applications is an early signal checkpoint
- 500 applications is a serious lower-bound job-search volume
- 750–1,000 applications is a realistic base-case planning range
- 1,500 applications is an ugly but plausible cold-market worst-case scenario

## Disclaimer

This is not a deterministic prediction. It is a planning model. The real job market is noisy, delayed, and affected by role fit, referrals, resume quality, geography, timing, hiring freezes, applicant volume, and interview performance.
