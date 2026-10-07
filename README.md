# Marketing & Channel Performance

This project analyses **marketing investment, channel performance, customer acquisition economics, and platform attribution** across a **2024–2025 marketing dataset** using **MySQL and Power BI**.

The objective was to move beyond basic campaign reporting and determine **which marketing investments generate profitable returns, how efficiently channels convert traffic, whether acquired customers justify acquisition costs, and how closely platform-reported performance reflects actual sales.**

**Tools:** MySQL · Power BI

---

## Marketing & Channel Performance Dashboard

### Page 1 — Campaign Performance

**Business Question**

> **Which campaigns are driving profitable revenue, and which are burning budget with poor return?**

**Key Insight**

Marketing investment expanded significantly in 2025, with spend increasing from **₦8.91M to ₦17.41M** while marketing profit increased from **₦30.21M to ₦38.00M**. The campaign portfolio also improved, with High/Excellent campaigns increasing from **31.75% to 67.91%** and Poor campaigns declining from **32.82% to 10.12%**.

However, overall marketing efficiency declined as investment scaled: **ROAS fell from 9.00x to 6.40x**, indicating that the additional spend generated lower returns than the 2024 investment base.

**Business Implication**

Marketing growth should be managed through **incremental return and campaign-level profitability**, rather than simply increasing total spend. Campaign quality improved, but scaling investment requires tighter control over where additional budget is deployed.

---

### Page 2 — Channel Performance & Funnel Efficiency

**Business Question**

> **Which traffic sources convert best, and where is marketing spend inefficient?**

**Key Insight**

Traffic conversion efficiency improved substantially in 2025. Conversion rate increased from **2.72% to 4.50%**, while CPA declined from **₦38.94 to ₦25.24**.

Traditional channels recorded a higher conversion rate of **7.76%** compared with **3.55% for digital channels**, while digital channels generated substantially more revenue at **₦160.38M versus ₦31.18M**. This demonstrates that **conversion rate alone is insufficient for evaluating channel value**; scale, revenue contribution, acquisition cost, and downstream customer value must also be considered.

**Business Implication**

Channel optimisation should move beyond traffic conversion metrics toward **full-funnel economics**, evaluating which channel-region combinations convert efficiently while generating meaningful revenue and customer value.

---

### Page 3 — Customer Acquisition Economics

**Business Question**

> **Are we acquiring customers efficiently, and are those customers worth what we are paying to acquire them?**

**Key Insight**

Customer acquisition scaled in 2025, with acquired customers increasing from **2,211 to 3,163**. However, average CAC increased from **₦4,030 to ₦5,503**, while average customer CLV increased only from **₦25,065 to ₦26,314**.

The reported CLV:CAC ratio declined from **13.0x to 9.0x**, while average projected payback increased from approximately **39 days to 67 days**. This indicates that although marketing became more effective at generating conversion events, **the economics of acquiring customers weakened as acquisition scaled**.

**Business Implication**

Customer acquisition should be evaluated on **CAC, CLV, payback, and customer quality together**, rather than optimising for conversion volume alone. Growth should prioritise acquisition sources capable of producing valuable customers at sustainable costs.

---

### Page 4 — Platform Attribution & Funnel Efficiency

**Business Question**

> **How much do platform-reported numbers diverge from actual sales, and where is the funnel leaking?**

**Key Insight**

The analysis identifies a substantial divergence between platform-attributed revenue and actual revenue. The reported attribution gap increased from **18.87% in 2024 to 75.43% in 2025**, while platform ROAS increased from **2.72x to 4.24x**.

Campaign-level comparisons also reveal that platform ROAS can differ materially from actual ROAS. For example, **Google Ads – West – Jan 2024** recorded platform ROAS of **1.07x** compared with actual ROAS of **172.46x**, while **Print Media – East – Mar 2025** recorded platform ROAS of **9.47x** compared with actual ROAS of **3.92x**.

This demonstrates that platform-reported performance does not always provide a reliable representation of realised business revenue.

**Business Implication**

Marketing decisions should distinguish between **platform-reported attribution and realised sales performance**, supported by a consistent attribution framework and clearly defined revenue, conversion, and customer-acquisition measures.

---

## Key Business Findings

* **Marketing investment scaled significantly:** spend increased **95.3% in 2025**, from **₦8.91M to ₦17.41M**.
* **Campaign portfolio quality improved:** High/Excellent campaigns increased from **31.75% to 67.91%**, while Poor campaigns fell from **32.82% to 10.12%**.
* **Marketing efficiency declined with scale:** ROAS decreased from **9.00x to 6.40x** despite higher marketing profit.
* **Traffic conversion improved:** conversion rate increased from **2.72% to 4.50%**, while CPA fell from **₦38.94 to ₦25.24**.
* **Customer acquisition became more expensive:** CAC increased **36.6%**, from **₦4,030 to ₦5,503**.
* **Customer value grew more slowly than acquisition cost:** average CLV increased only **5.0%**, from **₦25,065 to ₦26,314**.
* **Customer economics weakened:** reported CLV:CAC declined from **13.0x to 9.0x**, while projected payback increased from approximately **39 to 67 days**.
* **Digital dominates revenue contribution:** digital channels generated **₦160.38M** compared with **₦31.18M** from traditional channels, despite lower traditional-channel conversion rates.
* **Attribution reliability deteriorated:** the reported attribution gap increased from **18.87% to 75.43%** between 2024 and 2025.
* **Platform performance can diverge materially from actual performance:** campaign-level platform ROAS and actual ROAS show substantial differences across both high- and low-performing campaigns.
* **Geographic performance is uneven:** West repeatedly appears among stronger campaign outcomes, while Central appears frequently among weaker profitability, payback, and attribution results, warranting further regional investigation.

---

## Strategic Recommendations

* Shift marketing budget allocation toward **incremental profitability and sustainable return**, rather than spend growth alone.
* Evaluate campaigns at the **channel × region × campaign** level to identify where individual channels create or destroy value.
* Optimise acquisition using **CAC, CLV, and payback**, rather than conversion volume alone.
* Investigate recurring underperformance in the **Central region**, including targeting, customer quality, channel mix, and attribution.
* Use **actual revenue and realised business outcomes** alongside platform-reported metrics when evaluating campaign performance.
* Establish a consistent **marketing attribution framework** covering attribution windows, revenue definitions, conversion events, and customer acquisition.
* Separate **traffic efficiency from customer economics** so that improvements in CTR, conversion rate, or CPA are not mistaken for improvements in overall profitability.
* Prioritise marketing investment where **customer value, acquisition cost, campaign profitability, and measurement reliability** are jointly favourable.

---

## Data & Analytics Approach

**MySQL**

* Marketing data cleaning and transformation
* Campaign-level performance analysis
* Channel and regional aggregation
* Marketing spend, revenue, profit and ROAS calculations
* Funnel metric analysis
* Customer acquisition and CAC analysis
* CLV and CLV:CAC calculations
* Attribution-gap and payback analysis
* Campaign performance classification

**Power BI**

* Interactive marketing performance dashboard
* Executive KPI development
* Campaign profitability analysis
* Channel and funnel analysis
* Customer acquisition economics
* Platform vs actual revenue comparison
* Year-over-year performance analysis
* Campaign-level performance diagnostics

---

## Business Impact

The analysis moves marketing reporting from:

**"Which campaigns generated the most clicks and conversions?"**

to:

**"Which marketing investments generate profitable customers, what does it cost to acquire them, what value do they create, and can we trust the performance being reported by each platform?"**

The resulting framework provides a **data-driven foundation for marketing budget allocation, channel optimisation, customer acquisition strategy, and more reliable performance measurement.**

---

## Tech Stack

| Tool         | Role                                              |
|--------------|---------------------------------------------------|
| **MySQL**    | Data cleaning, transformation, ROAS, CAC, CLV & modelling |
| **Power BI** | Interactive dashboard, visualisation & executive reporting |




---
### Dashboard 1: Campaign Performance
<p align="left">
  <img src="https://cdn.prod.website-files.com/650ad291fd6cf342753e6a79/6ac650ca894dcc86f93c013a_Screenshot%20(7).png" alt="Profile Banner" width="100%"/>
</p>

### Dashboard 2: Channel Performance
<p align="left">
  <img src="https://cdn.prod.website-files.com/650ad291fd6cf342753e6a79/6ac650cab8cb40ca0c1fe117_Screenshot%20(8).png" alt="Profile Banner" width="100%"/>
</p>


### Dashboard 3: Customer Acquisition Economics
<p align="left">
  <img src="https://cdn.prod.website-files.com/650ad291fd6cf342753e6a79/6ac650caafce94ca97fc03b3_Screenshot%20(9).png" alt="Profile Banner" width="100%"/>
</p>


### Dashboard 4: Platform Attribution & Funnel Efficiency
<p align="left">
  <img src="https://cdn.prod.website-files.com/650ad291fd6cf342753e6a79/6ac650ca7ec1009529a7daea_Screenshot%20(10).png" alt="Profile Banner" width="100%"/>
</p>

























