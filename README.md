# 📊 Global Retail Intelligence & Revenue Assurance System

## 📌 Executive Summary
This project presents an end-to-end **Retail Analytics & Revenue Assurance System** designed to transform 530,000+ rows of fragmented transactional data into strategic business intelligence. Utilizing **Advanced Excel & Power Query (M-Logic)**, the system audits sales performance, quantifies revenue leakage through return analysis, and identifies consumer behavior patterns. The primary goal is to provide stakeholders with data-driven evidence to optimize inventory turnover and maximize net profitability.

---

## 🛠️ Technical Stack & Environment
* **Engine:** Microsoft Excel (Advanced)
* **ETL Tool:** Power Query (M-Language)
* **Analytical Logic:** Pivot Power, Nested Logical Functions, and Feature Engineering.
* **Documentation:** GitHub Markdown & Institutional Presentation format.

---

## 💎 Technical & Analytical Highlights
The analytical engine is built on a robust ETL pipeline designed for high-integrity data mining. Key technical implementations include:
* **Data Integrity Audits:** Automated null-value handling for `CustomerID` and cross-table validation to ensure a "Single Source of Truth."
* **Feature Engineering:** Created high-value calculated dimensions:
    * **Net Revenue Model:** Factorized Gross Sales vs. Returns ($Quantity \times UnitPrice$).
    * **Temporal Intelligence:** Extracted `Peak Hour`, `Weekday`, and `Month` for time-series forecasting.
    * **Customer Tiering:** Logic-based segmentation for "New" vs. "Repeat" buyers.
* **Process Optimization:** Appended heterogeneous datasets (Sales + Returns) into a unified star-schema-ready master table.

---

## 🏗️ Dataset Architecture
The project utilizes a multi-dimensional relational dataset structured into the following entities:
* **Transactional Data:** 530k+ unique records including `InvoiceNo`, `StockCode`, and `Quantity`.
* **Temporal Dimensions:** Time-stamped logs spanning a full fiscal cycle.
* **Geographic Dimensions:** Market-wise distribution across 38+ countries (UK, France, Germany, etc.).
* **Customer Entity:** Unique identifiers linked to purchase frequency and loyalty metrics.

---

## 💡 Key Analytical Findings (The "Business Truth")
* 📅 **The Q4 Surge:** Data confirms that **November** accounts for ~14% of annual revenue (₹14 Lakhs), identifying a heavy reliance on holiday seasonality.
* 🚧 **Revenue Leakage:** Identified a **4.6% Return Rate**, resulting in an erosion of **₹4.75 Lakhs** from the Gross Margin.
* 🕒 **The Golden Window:** Transactional density peaks between **10:00 AM and 3:00 PM**, revealing the optimal window for server-load management and ad-spend.

---

## 🔍 Strategic Operational Insights
* ⚠️ **Loss Mitigation System:** Flagged specific high-risk SKUs (e.g., *Regency Cakestand*) where return frequencies were disproportionately high compared to sales.
* 👥 **Market Concentration:** The UK market drives 90% of volume; however, **France and Germany** show a 0.5% higher Average Order Value (AOV), indicating premium market potential.
* 🛡️ **Inventory Efficiency:** Identified that the Top 10 products drive the majority of revenue, suggesting a **Pareto (80/20)** distribution in inventory value.

---

## 📊 Dashboard Intelligence Overview
* **Revenue Scorecard:** Real-time tracking of Gross vs. Net Revenue and Return Impact.
* **Temporal Trendline:** Longitudinal analysis of monthly growth and hourly spikes.
* **Customer Loyalty Map:** Donut-chart distribution of New vs. Returning customer contribution.
* **Geographic Heatmap:** Country-wise slicers for localized performance auditing.

---

## 🚀 Strategic Recommendations
1.  **Inventory Depth:** Scale up stock for "Top 10" SKUs 90 days prior to the November peak to prevent "Out-of-Stock" losses.
2.  **Quality Audit:** Targeted intervention for high-return categories to reduce the 4.6% leakage and save ~₹1L in annual logistics costs.
3.  **Basket Optimization:** Implement "Frequently Bought Together" bundling strategies to push the **AOV from ₹518 to ₹600+**.
4.  **Operational Scheduling:** Align warehouse staffing and server maintenance to avoid downtime during the 10 AM - 3 PM peak traffic window.

---

## 📜 Documentation & Files
* **Dataset & Analysis:** Due to the large file size (37MB), the complete Excel Binary Workbook is hosted on Google Drive for easy access.
* 🔗 **[Download Full Project Workbook (.xlsb)](https://drive.google.com/file/d/1iy-U6dgM-1yqtpYfnlqQWt3UUXCgwj1n/view?usp=sharing)**
