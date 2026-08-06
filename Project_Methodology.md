# Project Methodology

## 1. Project Scope

This project evaluates Royal Bank of Canada's:

- Financial performance
- Revenue composition
- Operating efficiency
- Credit-risk profile
- Balance-sheet trends
- Regulatory capital position
- Liquidity position
- Business-segment performance

The analysis period covers FY2023–FY2025 and Q1 2024–Q2 2026. The data cutoff is April 30, 2026.

## 2. Source Collection

Official public disclosures were collected from RBC Investor Relations. The principal source categories were:

- Annual Report
- Quarterly Report to Shareholders
- Supplementary Financial Information
- Pillar 3 Regulatory Disclosure
- Earnings Release

Each document was recorded in the workbook's source register before data was used.

## 3. Raw Data Capture

Data was entered into separate raw schedules for:

- Annual performance
- Quarterly performance
- Balance-sheet information
- Credit quality
- Capital and liquidity
- Business-segment results

Reported and adjusted measures were not mixed. The dashboard is primarily based on reported results.

## 4. Standardization

Raw data was reorganized into standardized schedules to improve comparability and formula consistency. Annual and quarterly periods were aligned, units were standardized, and intentionally undisclosed figures were left blank rather than replaced with zero.

## 5. KPI Calculation

The model calculates and analyzes:

- Revenue growth
- Net-income growth
- Diluted EPS
- Return on equity
- Efficiency ratio
- Operating leverage
- Pre-provision, pre-tax earnings
- Effective tax rate
- Provision for credit losses
- PCL-on-loans ratio
- Gross impaired loans
- GIL ratio
- Allowance for credit losses
- Net write-off ratio
- CET1 ratio
- Total capital ratio
- Liquidity coverage ratio
- Net stable funding ratio

## 6. Segment Analysis

Business-segment results were analyzed for:

- Personal Banking
- Commercial Banking
- Wealth Management
- Insurance
- Capital Markets
- Corporate Support

Segment revenue and net income were reconciled to consolidated totals where applicable.

## 7. Interactive Analysis

The workbook includes:

- Dropdown-based KPI selection
- Quarterly and annual trend analysis
- Dynamic segment ranking
- Normalized PivotTable source data
- Native PivotTable filters and slicers

## 8. Validation

The `25_Data_Audit` worksheet performs reconciliation tests, including:

- Revenue = net interest income + non-interest income
- Pre-tax income = revenue − PCL − non-interest expense
- Net income = pre-tax income − income taxes
- PPPT = pre-tax income + PCL
- Segment revenue reconciliation
- Segment net-income reconciliation
- Capital-ratio consistency
- Liquidity-threshold checks

The workbook was also scanned for visible formula errors such as `#REF!`, `#DIV/0!`, `#VALUE!`, `#NAME?`, and `#N/A`.

## 9. Limitations

- The project relies on publicly reported information.
- Some segment metrics are not separately disclosed and remain blank.
- FY2023 LCR and NSFR were not collected from the selected source set.
- The analysis is historical and does not constitute an investment recommendation.
