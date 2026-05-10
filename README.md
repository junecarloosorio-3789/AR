# AR Analytics Dashboard

A self-contained, single-file analytics dashboard for Accounts Receivable data (2024–2026).

## How to open

Just open `index.html` in any modern browser — no server or installation needed.

> **GitHub Pages:** Enable Pages in your repo settings (source: `main` branch, root `/`) and share the generated URL with the team.

## What's inside

| Section | What you get |
|---|---|
| **Summary** | AR balance, DSO, overdue buckets, collection rate KPIs |
| **DSO Trend** | Monthly / quarterly DSO trend by channel & class |
| **Customer Drilldown** | Deep-dive into a single customer's history |
| **Year Comparison** | Side-by-side AR metrics across years |
| **Month Comparison** | Compare any two months head-to-head |
| **Channel Comparison** | BH / IR / OR performance breakdown |
| **Collection Comparison** | Collection rates over time |
| **Executive Report** | New customer acquisition, cohort retention & repeat-order analysis |
| **Customers** | Full customer table with DSO, sales and collection data |
| **Refresh Data** | Upload a new Excel export to update all charts |

## Filters

Every page responds to the **Channel** and **Classification** filters in the top bar. The Executive Report also has its own filter row.

Click any **blue number** in the Executive Report tables to open a customer list panel showing names, channel, class, and sales for that segment.

## Data

Data covers **Jan 2024 – May 2026** (6,089 transaction rows, 485 unique customers).  
Source: `AR_Details_with_Sales_20242026.xlsx`

To refresh with newer data, go to **Refresh Data** in the sidebar and upload the updated Excel file. The dashboard will regenerate all charts automatically and offer a download of the updated HTML.

## Requirements

- A modern browser (Chrome, Edge, Firefox, Safari)
- Internet connection for fonts and charting library (loaded from CDN)
- No installation, no backend, no database
