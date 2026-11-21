# Customer Segmentation & Explainable Churn Prioritization Model

**Track:** Data Analytics | **Level:** Beginner-Friendly | **Estimated Time:** 90–120 Minutes  
**Submission Requirement:** One public or view-only link.

This repository delivers an explainable customer segmentation model, a transparent rule-based churn-risk score (0–100), rigorous edge-case validation, and a strategic recommendation memo with targeted retention playbooks for high-value cohorts.

---

## 🎯 Passing Checklist & Deliverables Verification

- [x] **Useful Behavioral & Account Features:** Evaluated contract commitment, support ticket velocity, tenure maturity, and payment instruments.
- [x] **Customer Segments / Cohorts Created & Explained:** Formed 4 explainable segments separating high-friction accounts (100% churn) from loyal anchors (0% churn).
- [x] **Reproducible Churn-Risk Score:** Designed an explainable 100-point scoring model with 100% precision in separating churned from retained accounts.
- [x] **Edge-Case Validation:** Stress-tested 4 complex boundary scenarios (silent churners, high tickets on contracts, boundary tenures, veteran anchors).
- [x] **Optional Portfolio Upgrade:** Prescribed specific retention playbooks for each high-value segment in a formal executive memo.

---

## 📁 Repository Deliverables Manifest

| Deliverable | File | Description |
| :--- | :--- | :--- |
| **Recommendation Memo** | [`recommendation_memo.md`](recommendation_memo.md) | Formal executive memo with segment tables, scoring rules, and retention playbooks. |
| **Analysis Notebook** | [`customer_segmentation_analysis.ipynb`](customer_segmentation_analysis.ipynb) | Jupyter Notebook with feature engineering, scoring engine, edge-case tests, and visual distributions. |
| **Segment Table & Excel Model** | [`segment_table.xlsx`](segment_table.xlsx) | Multi-sheet workbook: Segment Overview, Scored Customers, Scoring Matrix, and Edge Case Tests. |
| **Scored Dataset** | [`customer_segments_scored.csv`](customer_segments_scored.csv) | Enriched subscriber dataset with component scores, total churn-risk score, risk tier, and segment labels. |
| **Clean Source Dataset** | [`customer_churn_cleaned.csv`](customer_churn_cleaned.csv) | Verified clean source data used for the segmentation model. |
| **Pipeline Script** | [`generate_task3_deliverables.py`](generate_task3_deliverables.py) | Python automation script executing the segmentation and scoring pipeline end-to-end. |

---

## 📊 Summary of Customer Segments & Risk Tiers

| Segment Cohort | Count | Churn-Risk Score | Historical Churn | Monthly Revenue | Prescribed Retention Action |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Segment 1: High-Friction Flight Risks** | 7 (46.7%) | **90.0 / 100** | **100.0%** | ₹409.93 | Immediate VIP Concierge Call within 24h + 1-Month Billing Credit + Guided Onboarding. |
| **Segment 2: Contracted Friction Watchlist** | 2 (13.3%) | **32.5 / 100** | **0.0%** | ₹129.98 | Proactive Support Audit + 15% Annual Renewal Upgrade Discount. |
| **Segment 3: Enterprise Strategic Anchors** | 4 (26.7%) | **2.5 / 100** | **0.0%** | ₹599.96 | Dedicated Technical Account Manager (TAM) + Quarterly Business Review (QBR). |
| **Segment 4: Stable Core Subscribers** | 2 (13.3%) | **15.0 / 100** | **0.0%** | ₹129.98 | Automated Loyalty Milestone Recognition + Contract Renewal Rate Lock. |
