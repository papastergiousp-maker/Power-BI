# Power BI Dashboards

A collection of Power BI dashboards I built across finance, retail, operations, and healthcare. Each project includes the **\`.pbix\` file for download** and screenshots of the result.

**Stack:** Power BI Desktop · DAX · Custom KPI measures · Dynamic slicers

---

## Dashboards

### 1. Eurobank Financial Analysis 2022–2024
**Business question:** How did Eurobank's financial performance evolve from 2022 to 2024, and how does it compare to the European banking average?

**Headline numbers:**
- Net Interest Income grew **+72%** over 2 years (€1,456m → €2,504m)
- Cost-to-Income improved from **46.8% → 33.0%** — significant efficiency gains
- ROE **16.9%** in 2024 (above the European banking average ~12%)
- Loan-to-Deposit at **68.3%** — healthy liquidity, well below the 80% risk threshold
- Net Profit **+27% YoY** in 2024

All figures sourced directly from official Eurobank Annual Report PDFs (no pre-cleaned datasets). Pipeline: PDF extraction → pandas → SQLite → SQL KPI queries → Power BI with custom DAX measures.

---

### 2. Supermarket Sales & KPI Dashboard
**Business question:** Which product lines and customer segments drive the most revenue and gross income in a multi-branch supermarket?

**Key insights:**
- **$41.77M** total revenue across 1,000 orders
- Health & Beauty led gross income at **$7.9M** (highest margin category)
- Fashion Accessories drove the highest order volume (**17.8%** of total)
- Female customers generated higher average basket value across all branches
- Dynamic slicers by branch / gender / product line

---

### 3. Operational KPI & Quality Control Dashboard
**Business question:** Where are the performance gaps in a multi-location operation, and what is the financial cost of defects and fatal errors?

**Key insights:**
- **131K** total tasks monitored across all locations
- Overall defect rate: **20%** — fatal error rate: **8%**
- Overall quality score: **71.75/100** (below the 80% industry benchmark)
- Supervisor-level breakdown exposes clear performance gaps between locations
- Designed for management-level decision-making, not just reporting

---

### 4. Super Store Dashboard
Regional sales and product-category performance breakdown for a multi-region retail operation.

### 5. Hospital Analytics Dashboard
Healthcare admissions and operational KPIs.

### 6. COVID-19 Global Tracker
Global pandemic spread, recovery rate trends, and country-level analysis.

### 7. DAX Assignment
Reference work demonstrating custom DAX measures, calculated columns, and KPI logic patterns.

---

## How to use

1. Download the relevant **\`.pbix\`** file from this repo.
2. Open it in **Power BI Desktop** (free download from Microsoft).
3. The dashboard is fully interactive — use the slicers to filter.

## More of my work

- Full portfolio: [My_Projects](https://github.com/papastergiousp-maker/My_Projects)
- ETL pipelines that feed these dashboards: [ETL_Pipelines](https://github.com/papastergiousp-maker/ETL_Pipelines)
- Tableau equivalents: [Tableau Public profile](https://public.tableau.com/app/profile/spyros.papastergiou)
