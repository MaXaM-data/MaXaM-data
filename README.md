# Hi, I'm Max 👋

Early-career **Data Analyst** with a background in **compliance-heavy government operations**.  
I like turning messy operational data (SLAs, risks, caseloads, shipping, etc.) into clean, auditable dashboards in **Power BI** – with a bit of **Python** when privacy or data cleaning is involved.

- 🔎 Interested in: operational analytics, Cyber GRC, supply chain / logistics, public sector data
- 🏛️ Day job: working in the UK public sector on caseloads, risk and compliance
- 🎓 Studying towards: **PL-300 (Power BI Data Analyst)**

---

## 🔧 Tech & Tools

- **Languages:** SQL (joins/filters/aggregations), Python (`pandas` for cleaning & simple ETL), DAX  
- **Analytics & BI:** Power BI (Power Query, data modelling, KPIs, time intelligence), Excel  
- **Cloud & Governance:** Azure Fundamentals (AZ-900), Data Fundamentals (DP-900), APM PFQ  
- **Data themes:** SLA monitoring, risk scoring, GDPR-aware reporting, star schema modelling

---

## 📊 Portfolio Projects

### 1. Cyber GRC Risk Monitor

> Power BI dashboard for tracking **vulnerability SLAs**, **breach rate** and **critical server risk**.

- Built on a vulnerability scan–style dataset (Kaggle).
- Star schema with `Fact_Findings` + dimensions for assets, vulnerabilities, severity, teams and dates.
- Page 1: **Enterprise Vulnerability Risk Monitor** – KPIs for open vulns, SLA breach count/rate, critical servers; SLA breaches by department; severity mix.
- Page 2: **Server Vulnerability Details** – server-level table (CVSS, OS, days open) with slicers and a treemap of **top attack vectors**.
- Designed so **row-level security by department** can be added for real-world use.

🔗 **Repo:** [Cyber GRC Risk Monitor](https://github.com/MaXaM-data/cyber-grc-risk-monitor)

---

### 2. Global Supply Chain & Logistics Dashboard

> End-to-end project combining **Python (pandas)** for PII anonymisation with **Power BI** for SLA & margin analysis.

- Uses the **DataCo Supply Chain** dataset (~180k orders).
- Python script to strip **customer PII** (emails, names, addresses, passwords) and export a GDPR-style anonymised CSV.
- Star schema in Power BI with `Fact_Orders` + dimensions for customer, product, geography, shipping mode and date.
- **Page 1 – SLA & Margin Overview**
  - KPIs: Total Orders, Total Sales, Total Profit, Late Delivery Risk %, Net Profit Margin, Avg Days to Ship.
  - Late Delivery Risk % by Shipping Mode, Net Profit Margin by Market, SLA risk over time.
- **Page 2 – Commercial Insights & Profit Analysis**
  - Shows that **Same Day shipping is the least profitable mode globally**.
  - Quantifies that in **LATAM**, late deliveries earn ~**7% less profit per order** than on-time shipments.
  - Order volume & shipping mode mix by market to give context.

🔗 **Repo:** [Global Supply Chain & Logistics Dashboard](https://github.com/MaXaM-data/global-supply-chain-logistics-dashboard)

---

Currently focusing on:

- Deepening **Power BI + DAX** (time intelligence, advanced modelling)
- Using **Python + pandas** for data cleaning, anonymisation and simple ETL workflows
- Building more **domain-relevant projects** around risk, SLAs and public sector operations

---

## 📫 Contact

- 💼 LinkedIn: *[https://www.linkedin.com/in/max-lee-21b61239a/](url)*  
- 📧 Email: *maxam.data@gmail.com*  
