# 📊 VirtuBox Data Analyst Assessment

<p align="center">
  <strong>Turning Raw Data into Meaningful Insights</strong><br>
  Sales Performance • Customer Analytics • Data Quality
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-Analysis-blue?logo=python" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-Data%20Cleaning-150458?logo=pandas" alt="Pandas">
  <img src="https://img.shields.io/badge/Google%20Sheets-Reporting-34A853?logo=googlesheets" alt="Google Sheets">
  <img src="https://img.shields.io/badge/Looker%20Studio-Dashboard-4285F4" alt="Looker Studio">
</p>

---

## 📌 Project Overview

This project analyzes the **UCI Online Retail transaction dataset** to evaluate sales performance, customer activity, cancellation patterns, and data quality. The objective is to transform raw transaction data into actionable business insights and recommendations.

| 📅 Analysis Period            | 🛠️ Tools Used                               |
| ----------------------------- | -------------------------------------------- |
| December 2010 – December 2011 | Python, Pandas, Google Sheets, Looker Studio |

## 📂 Repository Contents

| File                                   | Description                                                     |
| -------------------------------------- | --------------------------------------------------------------- |
| 📓 `Online_Retail_Data_Analysis.ipynb` | Data cleaning, exploratory analysis, calculations, and findings |
| 📈 `monthly_sales.png`                 | Monthly sales trend visualization                               |
| 🌍 `country_sales.png`                 | Sales performance by country                                    |
| ↩️ `cancellation_analysis.png`         | Cancellation analysis visualization                             |

## 🧹 Data Cleaning & Preparation

* 📥 Started with **541,909 transaction rows**.
* 🧹 Removed **5,268 exact duplicate rows**.
* 📝 Replaced missing product descriptions with `Unknown Description`.
* 👤 Retained missing `CustomerID` values without inventing customer identities.
* 🧮 Calculated sales value as `Quantity × Unit Price`.
* 🔎 Separated positive sales from cancellation and other non-positive transactions for relevant analyses.

## 📈 Key Findings

| Metric                            |                  Result |
| --------------------------------- | ----------------------: |
| 💷 Positive Sales Value           |      **£10,550,599.44** |
| 🧾 Unique Positive-Sales Invoices |              **19,866** |
| 📦 Unique Products Sold           |               **3,920** |
| 🌍 Countries Represented          |                  **38** |
| 🇬🇧 UK Share of Positive Sales   | **Approximately 84.9%** |
| 🏆 Highest Monthly Sales          |       **November 2011** |

### 🔍 Business Insights

* **Monthly performance:** November 2011 recorded the highest sales in the analyzed period.
* **Geographic concentration:** The United Kingdom contributed approximately 84.9% of positive sales value.
* **Customer data quality:** Missing customer IDs limit customer-level analysis.
* **Cancellations:** Cancellation records warrant further investigation, including manual entries.
* **Reporting limitation:** December 2011 data ends on December 9, so it is not comparable to a complete month.

## ⚠️ Limitations & Considerations

* Some transactions have missing `CustomerID` values.
* Recorded cancellation values do not necessarily represent confirmed refunds.
* Exceptionally large transactions should be checked against source records before drawing conclusions.
* December 2011 is incomplete.
* Sales value represents recorded transaction value, **not profit**.

## 💡 Recommendations

1. 🔎 Investigate cancellation patterns and manual entries.
2. 🛡️ Verify unusually large transactions against source records.
3. 👤 Improve customer ID completeness and data capture.
4. 🤝 Develop retention strategies for high-value customers.
5. 🌐 Evaluate opportunities in international markets.
6. 📊 Monitor monthly performance while accounting for incomplete reporting periods.

## 🤖 AI Assistance & Validation

AI tools supported concept clarification, troubleshooting, and the review of insights and recommendations. The analysis was executed in Python, and the generated outputs were checked against the analysis results.

## 🔗 Additional Deliverables

<p align="center">
  <a href="https://docs.google.com/spreadsheets/d/10kbkpXNpZEGI2xyT3GbbyyUvaK6nm30GfYu4uODHF6Q/edit?gid=316326430#gid=316326430">
    📗 <strong>Google Sheets Analysis</strong>
  </a>
  &nbsp; • &nbsp;
  <a href="https://docs.google.com/presentation/d/1prh14b0q7kenf8QKz0PlEF_kVuJeEL8DFgMJOjsP2EM/edit?slide=id.h48e02e740f4405a6_0_46#slide=id.h48e02e740f4405a6_0_46">
    📊 <strong>Management Presentation</strong>
  </a>
  &nbsp; • &nbsp;
  <a href="https://drive.google.com/drive/folders/1LBWDXihTteXtsF4-vm2NEdECRqadO0va?usp=drive_link">
    📁 <strong>Google Drive Folder</strong>
  </a>
</p>

---

<p align="center">
  <strong>📊 Better Data. Better Decisions.</strong><br>
  <sub>VirtuBox Data Analyst Assessment</sub>
</p>
