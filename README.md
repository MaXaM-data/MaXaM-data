# Hi, I'm Max 👋

Aspiring **Data Engineer** with a background in **compliance-heavy UK public sector operations**.  
I’m focused on building **reliable, repeatable data pipelines** — ingest → clean → validate → publish — and using **Power BI** as the final consumer layer to show the data is usable.

I’m especially interested in data roles that support **health and social care outcomes**, where data quality, governance and auditability really matter.

- 🔎 Interested in: data pipelines, data quality, monitoring, governance-aware delivery, public sector / health data
- 🏛️ Day job: UK public sector role involving evidence checks, risk, and audit trails
- 🎓 Studying towards: **PL-300 (Power BI Data Analyst)** to strengthen the reporting layer (alongside pipeline work)

---

## 🔧 Tech & Tools

- **Python:** `pandas` for ingestion/cleaning, column-level controls, basic QA checks (row/column counts, null checks)
- **SQL:** joins, filters, aggregations (for extraction and validation)
- **BI / Consumer layer:** Power BI (Power Query, modelling, DAX) to validate outputs and communicate insights
- **Cloud fundamentals:** AZ-900, DP-900
- **Engineering themes:** staging vs publish, repeatability, validation, documentation, privacy-aware preparation

---

## 📦 Portfolio Projects

### 1) Vulnerability Risk Monitor (Portfolio Project)

> A “pipeline to dashboard” project: model findings data cleanly and surface reliable operational metrics.

- Built on a vulnerability scan–style dataset (Kaggle).
- Modelled the data into a star schema (`Fact_Findings` + dimensions for assets, severity, teams, dates) to support stable reporting.
- Built measures for ageing (days open), breach-style service targets, and critical-item counts.
- Designed so **Row-Level Security (RLS)** could be added by department in a real environment.

🔗 Repo: https://github.com/MaXaM-data/cyber-grc-risk-monitor

---

### 2) Global Supply Chain & Logistics Dashboard

> Demonstrates a simple, repeatable **privacy-aware preparation step** + QA, then a reporting layer.

- Uses the **DataCo Supply Chain** dataset (~180k orders).
- Python script removes **direct identifiers** (e.g., names/emails/addresses/passwords) and exports a **PII-reduced** CSV for analysis.  
  **Note:** This is **not** a claim of full anonymisation or formal GDPR compliance — it’s a practical data-minimisation step for a portfolio project.
- Added basic QA checks (row/column counts before vs after) to confirm records weren’t accidentally filtered during cleaning.
- Built a star schema in Power BI (`Fact_Orders` + dimensions for customer, product, geography, shipping mode, date) and measures for delivery/service metrics and profitability.

🔗 Repo: https://github.com/MaXaM-data/global-supply-chain-logistics-dashboard

---

## What I’m building next

- Stronger **data quality checks** (e.g., null-rate thresholds, schema checks, duplicate checks)
- A small “orchestration-style” pattern (staging → validate → publish) to simulate real pipelines
- Learning production concepts with guidance: incremental loads, monitoring/alerts, and incident handling

---

## 📫 Contact
- LinkedIn: https://www.linkedin.com/in/max-lee-21b61239a/
- Email: maxam.data@gmail.com