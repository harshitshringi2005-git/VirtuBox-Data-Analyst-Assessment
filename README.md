\# VirtuBox Data Analyst Assessment



\## Project Overview



This project analyzes the UCI Online Retail transaction dataset to understand sales performance, customer activity, cancellations, and data quality.



\*\*Analysis period:\*\* December 2010 – December 2011

\*\*Tools:\*\* Python, Pandas, Google Sheets, Looker Studio



\## Repository Contents



\* `Online\_Retail\_Data\_Analysis.ipynb` — Python notebook for data cleaning, analysis, and calculations.

\* `monthly\_sales.png` — Monthly sales trend chart.

\* `country\_sales.png` — Sales performance by country.

\* `cancellation\_analysis.png` — Cancellation analysis chart.



\## Data Cleaning



\* Original dataset: 541,909 rows.

\* Removed 5,268 exact duplicate rows.

\* Replaced missing product descriptions with `Unknown Description`.

\* Retained missing CustomerID values without inventing customer identities.

\* Calculated sales value as Quantity × Unit Price.



\## Key Findings



\* Positive sales value: £10,550,599.44.

\* Unique positive-sales invoices: 19,866.

\* Unique products sold: 3,920.

\* The United Kingdom contributed approximately 84.9% of positive sales value.

\* November 2011 had the highest monthly sales.

\* December 2011 data is incomplete and ends on December 9.



\## Limitations



\* Many transactions have missing CustomerID values.

\* Recorded cancellation values are not necessarily confirmed refunds.

\* Exceptionally large transactions should be verified against source records.

\* December 2011 is an incomplete month.



\## Recommendations



1\. Investigate cancellation patterns and manual entries.

2\. Verify unusually large transactions against source records.

3\. Improve CustomerID completeness.

4\. Retain high-value customers and explore international markets.

5\. Monitor monthly sales trends while accounting for incomplete periods.



\## AI Assistance



AI tools supported concept clarification, troubleshooting, and reviewing insights and recommendations. The analysis was executed in Python, and the generated outputs were checked against the analysis results.



\## Additional Deliverables

* [Google Sheets Analysis](https://docs.google.com/spreadsheets/d/10kbkpXNpZEGI2xyT3GbbyyUvaK6nm30GfYu4uODHF6Q/edit?gid=316326430#gid=316326430)
* [Management Presentation](https://docs.google.com/presentation/d/1prh14b0q7kenf8QKz0PlEF_kVuJeEL8DFgMJOjsP2EM/edit?slide=id.h48e02e740f4405a6_0_46#slide=id.h48e02e740f4405a6_0_46)
* [Google Drive Assessment Folder](https://drive.google.com/drive/folders/1LBWDXihTteXtsF4-vm2NEdECRqadO0va?usp=drive_link)


