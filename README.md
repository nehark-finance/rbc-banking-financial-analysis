# Royal Bank of Canada Financial Analysis

An independent Excel-based finance and accounting portfolio project evaluating Royal Bank of Canada's financial performance, operating efficiency, credit risk, capital adequacy, liquidity, and business-segment performance.

![Executive Dashboard](images/RBC_Executive_Dashboard.png)

## Project Overview

- **Company:** Royal Bank of Canada
- **Industry:** Banking and Financial Services
- **Analysis period:** FY2023–FY2025 and Q1 2024–Q2 2026
- **Data cutoff:** April 30, 2026
- **Currency:** Canadian dollars
- **Reporting unit:** CAD millions unless otherwise stated
- **Primary tool:** Microsoft Excel
- **Project type:** Independent finance and accounting portfolio project

## Objective

The project converts publicly available RBC annual, quarterly, supplementary, and regulatory disclosures into a structured Excel model and interactive analytical dashboard.

The analysis addresses the following questions:

1. Is RBC generating sustainable revenue and earnings growth?
2. How are net interest income and non-interest income changing?
3. Are operating expenses growing faster or slower than revenue?
4. How has return on equity changed?
5. Is credit quality strengthening or deteriorating?
6. How have provisions for credit losses and impaired loans changed?
7. Which business segments are contributing most to earnings?
8. Does RBC maintain sufficient regulatory capital and liquidity?

## Key Findings

- FY2025 revenue reached **CAD 66.6 billion**, while net income reached **CAD 20.4 billion**.
- FY2025 ROE improved to **16.3%**, and the efficiency ratio declined to **54.9%**.
- Total provisions for credit losses increased through FY2025, reflecting a more normalized credit cycle.
- Q2 2026 net income was **CAD 5.5 billion**, up year over year but lower sequentially.
- RBC maintained a **13.5% CET1 ratio** and a **126% liquidity coverage ratio** in Q2 2026.
- Personal Banking remained the largest segment earnings contributor, supported by diversification from Wealth Management and Capital Markets.

## Excel Model Features

- Annual and quarterly financial-statement analysis
- Credit-risk and asset-quality analysis
- Regulatory capital and liquidity analysis
- Business-segment performance analysis
- KPI calculations and trend analysis
- Interactive dropdown-based analysis
- Advanced formulas using `INDEX`, `MATCH`, `SUMIFS`, `IFERROR`, `RANK`, and `COUNTIF`
- Normalized long-format PivotTable source
- Native PivotTable with slicers
- Formula-driven audit and reconciliation checks
- Executive dashboard and analyst commentary

## Repository Structure

```text
rbc-banking-financial-analysis/
├── README.md
├── DISCLAIMER.md
├── .gitignore
├── data/
│   └── RBC_Banking_Financial_Analysis.xlsx
├── images/
│   ├── RBC_Executive_Dashboard.png
│   ├── RBC_Interactive_Analysis.png
│   ├── RBC_Advanced_Excel.png
│   └── RBC_Native_PivotTable.png
└── documentation/
    ├── Project_Methodology.md
    ├── KPI_Definitions.md
    ├── Source_Register.md
    └── Workbook_Guide.md
```

## Workbook Navigation

The workbook contains 26 organized worksheets covering project setup, source records, raw data, standardized schedules, analytical outputs, dashboards, advanced formulas, PivotTable data, and audit checks.

For a complete sheet-by-sheet explanation, see [Workbook Guide](documentation/Workbook_Guide.md).

## Methodology

The model follows a traceable process:

1. Collect official RBC annual, quarterly, supplementary, and regulatory disclosures.
2. Record each source in a formal source register.
3. Enter and validate raw reported data.
4. Standardize annual, quarterly, balance-sheet, credit-risk, capital, liquidity, and segment schedules.
5. Calculate performance and risk indicators.
6. Build interactive analytical outputs and dashboards.
7. Reconcile totals and scan the workbook for formula errors.

See [Project Methodology](documentation/Project_Methodology.md) for more detail.

## Data Sources

The analysis uses publicly available RBC Investor Relations reports, including the 2025 Annual Report, quarterly reports, supplementary financial information, Q2 2026 Pillar 3 disclosures, and the Q2 2026 earnings release.

See [Source Register](documentation/Source_Register.md).

## Skills Demonstrated

- Financial statement analysis
- Banking KPI interpretation
- Credit-risk analysis
- Capital and liquidity analysis
- Financial modelling in Excel
- Data validation and reconciliation
- PivotTables and slicers
- Dashboard design
- Analytical commentary
- Documentation and source traceability

## How to Use the Workbook

1. Download `data/RBC_Banking_Financial_Analysis.xlsx`.
2. Open it in Microsoft Excel.
3. Enable editing if prompted.
4. Review `01_Cover` and `02_Project_Charter`.
5. Use `19_Dashboard` for the executive overview.
6. Use `21_Interactive_Analysis`, `22_Advanced_Excel`, and `26_Native_PivotTable` for interactive analysis.
7. Review `25_Data_Audit` for validation checks.

## Author

**Neha R K**  
Accounting and Finance | Professional Accounting | Financial Technology  
[LinkedIn](https://www.linkedin.com/in/nehark/)

## Disclaimer

This is an independent educational portfolio project. It is not affiliated with or endorsed by Royal Bank of Canada. It is not investment advice. All company data is derived from publicly available disclosures and remains subject to the original source documents.
