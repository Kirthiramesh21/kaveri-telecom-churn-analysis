# Phase 1 — Business Context
## Project: Subscriber Churn & ARPU Recovery Analysis — Kaveri Telecom

---

## 1. Company Scenario

**Kaveri Telecom** is a fictional regional telecom operator headquartered in Bengaluru, serving ~8.2 million subscribers across Karnataka, Tamil Nadu, and Andhra Pradesh. Founded in 2009, it competes against national giants by positioning on regional-language customer service, strong rural coverage, and value pricing.

**Subscriber mix:** ~78% prepaid, ~22% postpaid
**Revenue (FY25):** ₹2,140 crore
**Channels:** ~12,000 retail recharge points, MyKaveri app, call centres

## 2. Industry Context

The Indian telecom market is one of the most price-competitive in the world. Since the 2016 price war, operators have faced sustained ARPU pressure, consolidation, and rising customer expectations on data speed and digital self-service. Subscribers face near-zero switching costs due to Mobile Number Portability (MNP). 5G rollout by national players is intensifying competitive pressure on regional operators.

## 3. Business Problem

Over the last 4 quarters, Kaveri Telecom has experienced:

- Monthly churn rising from **2.1% → 3.4%** (prepaid churn worst at 3.9%)
- Blended ARPU declining from **₹152 → ₹138** (-9.2%)
- Net subscriber additions turning **negative** in the last 2 quarters
- Customer acquisition cost (CAC) rising 18% as the company spends more on promotions to replace lost subscribers

Combined effect: an estimated **₹190+ crore annualised revenue erosion** if trends continue. Leadership does not know *which* customers are leaving, *why*, or *which* retention levers offer the best ROI.

## 4. Strategic Objectives (FY27)

| # | Objective | Target |
|---|-----------|--------|
| O1 | Reduce blended monthly churn | 3.4% → ≤2.5% |
| O2 | Recover ARPU | ₹138 → ≥₹150 |
| O3 | Improve high-value subscriber retention | 95%+ annual retention in top-value decile |
| O4 | Shift retention spend from blanket promos to targeted offers | ≥60% of retention budget targeted |

## 5. Stakeholders

| Stakeholder | Role | Primary Interest |
|---|---|---|
| CEO | Sponsor | Subscriber growth, market position |
| CFO | Approver | Revenue protection, ROI of retention spend |
| CMO | Key user | Targeting, campaign effectiveness, CAC |
| Head of Customer Experience | Key user | Complaint drivers, NPS, service quality |
| Head of Network Operations | Contributor | Network-quality-driven churn |
| Regional Sales Heads (3 circles) | Contributors/users | Circle-level performance |
| Data & Analytics Team | Delivery | Data quality, modelling, dashboards |

## 6. Key Performance Indicators

| KPI | Definition | Current | Target |
|---|---|---|---|
| Monthly churn rate | Churned subscribers ÷ opening base | 3.4% | ≤2.5% |
| ARPU | Total service revenue ÷ avg. active subscribers | ₹138 | ≥₹150 |
| CLV | Projected margin over expected subscriber lifetime | TBD | +15% |
| Net adds | Gross adds − churned subscribers | Negative | Positive |
| Recharge frequency (prepaid) | Avg. recharges per subscriber per month | Declining | Stabilise |
| Retention offer ROI | Incremental retained revenue ÷ offer cost | Not measured | ≥3x |

> **[KURT'S DECISION #1 — Churn definition]** Postpaid churn is clean (account closure / port-out). Prepaid churn is genuinely ambiguous — is a subscriber "churned" after 30, 60, or 90 days of no recharge/usage? This single definition changes every number in the project. Choose and justify. (Industry practice varies; TRAI uses its own VLR-based view. Interviewers love this question.)

> **[KURT'S DECISION #2 — Scope]** Analyse prepaid + postpaid together, or focus the deep-dive on prepaid (78% of base, worst churn) with postpaid as a comparison segment? Tighter scope = sharper story.

> **[KURT'S DECISION #3 — Primary KPI tension]** Churn reduction and ARPU growth can conflict (cheap retention offers keep subscribers but dilute ARPU). Decide which is the north-star metric when they trade off, and state the rationale. This becomes the backbone of your Phase 9 recommendations.

## 7. Why Solving This Creates Business Value

1. **Revenue protection:** Halting the churn trend protects an estimated ₹190 crore of annualised revenue — far cheaper than replacing subscribers at rising CAC (retention is typically 5–7x cheaper than acquisition in telecom).
2. **Smarter spend:** Today's blanket promotions subsidise subscribers who would have stayed anyway. Targeting offers using churn-risk scoring redirects budget to genuinely at-risk, high-value subscribers.
3. **ARPU recovery:** Identifying upgrade-ready segments (data-heavy prepaid users suited to higher packs or postpaid migration) creates an upsell path that lifts ARPU without raising headline prices.
4. **Decision infrastructure:** The dashboards and churn-risk model become permanent assets — leadership moves from quarterly hindsight to weekly, segment-level visibility.

---
*Next: Phase 2 — Business Analysis (problem statement, business case, stakeholder analysis, process maps, requirements).*
