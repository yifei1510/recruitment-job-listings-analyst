# Excel and SPSS Recruitment Data Analysis

## Overview

This project analyses an Australian recruitment job listings dataset using Excel and SPSS.

The work focused on cleaning job listing records, matching company details, creating verification status fields, and producing descriptive analysis outputs that summarise the structure and quality of the dataset.

The project is designed as a data analysis portfolio example. It demonstrates practical spreadsheet preparation, company detail verification, SPSS frequency tables, crosstabs, and reporting.

![Project Overview](assets/spss_report/01_project_overview.png)

## Dataset

The dataset contains Australian job listing records with company and role information.

| Item | Value |
|---|---:|
| Job listing records analysed | 7,633 |
| Unique company names | 3,090 |
| Verified rows | 827 |
| Needs Detail rows | 6,806 |
| Verified row percentage | 10.8% |

Key fields used in the analysis:

- `Title`
- `Company`
- `Full Location`
- `Location`
- `State`
- `Category`
- `Level`
- `Detail`
- `Verification_Status`
- `Verified_Detail`

## Tools Used

- Microsoft Excel
- SPSS
- CSV data preparation
- SPSS syntax
- PDF / HTML reporting

## Workflow

1. **Data preparation in Excel**
   - Cleaned and organised job listing records.
   - Matched company names with verified company details.
   - Created verification status fields to separate verified records from records still requiring detail review.

2. **SPSS-ready dataset preparation**
   - Prepared a cleaned CSV version suitable for SPSS import.
   - Created a data dictionary and SPSS import syntax.
   - Added analysis-friendly variables such as verification status and company occurrence count.

3. **SPSS analysis**
   - Produced frequency tables for state, job category, level, and verification status.
   - Created crosstabs to compare verification coverage across states and job categories.
   - Reviewed high-frequency companies to identify records that could be prioritised for further validation.

4. **Report output**
   - Cleaned the original SPSS output into a portfolio-ready PDF and editable HTML report.
   - Removed syntax logs, import logs, warning messages, processor time, elapsed time, and repeated system metadata.

## Key Findings

- The dataset contains **7,633 job listing records** and **3,090 unique company names**.
- **827 rows** have verified company details.
- **6,806 rows** remain marked as `Needs Detail`.
- The verified row percentage is **10.8%**.
- NSW and QLD have the highest number of job listing records.
- The largest job category is `Other`, followed by `Administration & Office Support`, `Trades & Services`, `CEO & General Management`, and `Retail & Consumer Products`.
- Verification coverage can be improved by prioritising high-frequency company names and high-volume job categories.

## SPSS Analysis Outputs

### Job Listings by State

![Job Listings by State](assets/spss_report/02_state_frequency.png)

This output summarises the distribution of job listing records across Australian states and territories.

### Company Detail Verification Status

![Company Detail Verification Status](assets/spss_report/03_verification_status.png)

This output shows how many job listing rows have verified company details and how many still require further detail validation.

### Top Job Categories

![Top Job Categories](assets/spss_report/04_top_categories.png)

This output identifies the highest-volume job categories in the dataset.

### State by Verification Status Crosstab

![State by Verification Status](assets/spss_report/05_state_verification_crosstab.png)

This crosstab helps identify where company detail verification coverage is strongest or weakest by state.

## Cleaned Report Outputs

![Cleaned Report Outputs](assets/spss_report/06_clean_report_outputs.png)

The original SPSS output was cleaned into a more readable report format:

- [Cleaned PDF report](output/clean_spss_report/Reesby_Clean_SPSS_Report.pdf)
- [Editable HTML report](output/clean_spss_report/Reesby_Clean_SPSS_Report.html)

## Files Included

| File | Description |
|---|---|
| `report.pdf` | Original SPSS output report |
| `Reesby_SPSS_Analysis.sps` | SPSS analysis syntax |
| `output/spss_ready/Job_Listings_SPSS_Ready.csv` | SPSS-ready cleaned dataset |
| `output/spss_ready/Import_Job_Listings_SPSS_Ready.sps` | SPSS import syntax |
| `output/spss_ready/Job_Listings_SPSS_Data_Dictionary.csv` | Data dictionary |
| `output/clean_spss_report/Reesby_Clean_SPSS_Report.pdf` | Cleaned PDF analysis report |
| `output/clean_spss_report/Reesby_Clean_SPSS_Report.html` | Editable HTML report |
| `assets/spss_report/` | README images and analysis visuals |

## Limitations

- Not all company details have been verified.
- The dataset currently includes **827 verified rows** and **6,806 rows requiring further detail validation**.
- The analysis is descriptive and focuses on frequencies, crosstabs, verification coverage, and reporting readiness.
- The project does not use predictive modelling or inferential statistical testing.

## What I Learned

This project strengthened my ability to:

- Prepare spreadsheet data for statistical analysis.
- Use Excel to clean and match operational records.
- Use SPSS to generate frequency tables and crosstabs.
- Create verification status fields for data quality tracking.
- Convert raw SPSS output into a cleaner PDF and HTML report.
- Present data quality progress clearly without overstating completion.

## Summary

This project demonstrates a practical workflow for turning recruitment job listing data into a cleaned, analysable dataset and SPSS-style report. The work combines Excel-based preparation with SPSS descriptive analysis to support data quality review, company detail tracking, and reporting.
