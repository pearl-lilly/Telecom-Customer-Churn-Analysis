# 📊 Telecom Customer Churn Analytics – Power BI Project  
**Reducing Churn. Maximizing Customer Value. Driving Strategy.**

> This project leverages Power BI to uncover churn risks, revenue loss, and service-level drivers in a telecom dataset of over 7,000 customers. Two interactive dashboards transform raw data into business-ready insights that inform retention strategies and revenue optimization

---

<details>
<summary>🎯 Business Challenge</summary>

Telecom companies face a costly battle against churn. A **26.5% churn rate** signals urgent retention challenges, especially when high-revenue segments are affected.  Customer churn is a critical challenge for telecom companies, directly impacting revenue, profitability, and market share. Understanding why customers leave and who is at risk is paramount for developing effective retention strategies and sustaining growth. This project addresses this challenge by transforming raw customer data into actionable business intelligence.

</details>

---

<details>
<summary>📊 Dashboard 1: Customer Performance & Churn</summary>

<details>
<summary>📌 Objective</summary>

This dashboard provides a high-level view of:
- Customer attrition across **tenure segments**
- Revenue impact of churn by **contract type**
- Usage of **phone service**
- **Gender** breakdown
- Total charges by **payment method**

</details>

<details>
<summary>🔍 Key Insights & Actions</summary>

<details>
<summary>🕒 Churn by Tenure Segment</summary>

**Problem**:  
Churn is highest in the **0–12 months** and **61–72 months** tenure groups, indicating early disengagement and late-stage dissatisfaction.

**Action**:
- For **new customers**: Improve onboarding and first-90-day engagement.
- For **loyal customers**: Offer loyalty rewards and win-back offers near the 5-year mark.

</details>

<details>
<summary>📄 Revenue Loss by Contract Type</summary>

**Problem**:  
**Month-to-month** plans contribute heavily to churn, $1.9M lost  despite lower overall customer volume.  
**Two-year contracts** are more stable, bringing $6M in revenue and only $0.3M in churn loss.

**Action**:
- Incentivize customers to switch to **long-term contracts** through value bundling.
- Investigate why month-to-month users churn more: pricing? poor experience?

</details>

<details>
<summary>📞 Phone Service Usage & Churn Propensity</summary>

**Problem**:  
90.3% use phone service; 9.6% do not. The churn behavior of non-users isn't clearly shown but could suggest risk.

**Action**:
- Use filtering to analyze if **non-users churn more**.
- If so, bundle phone service with other plans to increase stickiness.

</details>

<details>
<summary>👥 Gender Distribution (Contextual Insight)</summary>

**Finding**:  
Almost equal split: 50.48% female, 49.52% male.

**Action**:
- Continue with **gender-neutral messaging**.
- Use filters to explore any churn trend by gender for future targeting.

</details>

<details>
<summary>💳 Total Charges by Payment Method</summary>

**Finding**:  
Most revenue comes from **electronic**, **bank**, and **credit card** users (~$4.7M each).  
**Mailed check** users contribute the least at $1.7M.

**Action**:
- Promote digital payment methods for convenience and loyalty.
- Explore if mailed check users have **higher churn or lower value**  if so, create targeted nudges.

</details>

</details>

</details>

---
![Screenshot 2025-06-20 111556](https://github.com/user-attachments/assets/9417c89e-1013-4294-9fa4-409a162de0e4)

<details>
<summary>📊 Dashboard 2: Service Impact & Customer Value</summary>

<details>
<summary>📌 Objective</summary>

This dashboard focuses on how service types and feature adoption affect churn and revenue:
- Internet service types: **Fiber**, **DSL**, **None**
- Revenue from **Multi-line service**
- Churn by **Online Security** feature
- Churn by **Paperless Billing** preference

</details>

<details>
<summary>🔍 Key Insights & Actions</summary>

<details>
<summary>🌐 Internet Service & Churn: High-Value, High-Risk</summary>

**Problem**:  
**Fiber Optic** brings in $7.4M but has $2.5M churn loss. DSL and non-internet users show lower churn.

**Action**:
- Investigate service quality, pricing, and support for Fiber customers.
- Create **targeted retention offers** for high-value Fiber users.

</details>

<details>
<summary>🔄 Multi-Line Service & Upselling Opportunity</summary>

**Finding**:  
Multi-line users generate $10.5M in revenue, far more than single-line ($4.6M).

**Action**:
- Promote **multi-line plans** with bundles and family discounts.
- Monitor churn for multi-line users  high-value customers must be retained.

</details>

<details>
<summary>🛡️ Online Security & Churn Reduction Power</summary>

**Problem**:  
Customers **without** Online Security churn at **41.77%**, compared to **14.61%** for those **with** it.

**Action**:
- Bundle Online Security with base plans.
- Emphasize security value in marketing and onboarding emails.

</details>

<details>
<summary>🧾 Paperless Billing & Hidden Churn Signals</summary>

**Problem**:  
Paperless billing users churn at **26.9%** vs. **16.3%** for those with traditional billing  a surprising risk factor.

**Action**:
- Audit the **digital billing experience**  possible pain points?
- Use email/SMS follow-ups or nudges to **re-engage paperless users**.

</details>

</details>

</details>

---
![Screenshot 2025-06-23 035035](https://github.com/user-attachments/assets/377d179d-1f2b-4c90-ae85-01f85cc5eadf)


<details>
<summary>📈 Key Metrics</summary>

- **Total Charges**: $16M  
- **Total Customers**: 7,043  
- **ARPU** (Average Revenue Per User): $2.28K  
- **Overall Churn Rate**: 26.5%

</details>

---

<details>
<summary>🧠 Business Impact</summary>

This analysis enables decision-makers to:

- Identify **high-risk customers** by contract, tenure, and service profile  
- Detect **financial leaks** from short-term contracts and neglected features  
- Launch **data-driven campaigns** to improve retention  
- Promote **high-retention services** like Online Security and Multi-Line

</details>

---



<details>
<summary>🛠️ Tools Used</summary>

- **Power BI Desktop**  
  - DAX Measures  
  - Interactive slicers & cross-filtering  
  - Custom KPIs: ARPU, Total Charges, Churn Rate  
  - Visuals: Bar charts, donut charts, stacked 100% columns

</details>

---

<details>
<summary>📎 Dataset</summary>

**Source**: [Telco Customer Churn – Kaggle Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

This dataset includes information about customer demographics, account information, service subscriptions, and churn labels.

</details>

---

<details>
<summary>🧾 Conclusion</summary>

This project demonstrates how data analytics can empower telecom companies to reduce churn and protect revenue. By breaking down customer behavior across tenure, contract types, service usage, and feature adoption, the dashboards offer practical, actionable insights for business leaders.

✅ Early-stage and long-term churn risks were clearly identified.  
✅ High-risk contract types and service offerings (e.g., month-to-month, Fiber Optic) were isolated.  
✅ Retention levers like Online Security and Multi-Line plans were highlighted.

The strength of this analysis lies not just in the visuals, but in how it translates raw data into real-world decisions from onboarding improvements to pricing strategy, loyalty campaigns, and service bundling.

Going forward, this project can be expanded with:
- Predictive churn modeling (e.g., logistic regression or decision trees)
- Regional churn analysis (if location data is added)
- Automated retention alerts via Power BI subscriptions or integrations

Ultimately, this project showcases my ability to use Power BI, DAX, and business context to drive meaningful decisions not just dashboards, but impact.

</details>


