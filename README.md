# Excel and SPSS Recruitment Data Analysis

## Overview

This project analyses an Australian recruitment job listings dataset using Excel and SPSS.

The work focused on cleaning job listing records, matching company details, creating verification status fields, and producing descriptive analysis outputs that summarise the structure and quality of the dataset.

The project is designed as a data analysis portfolio example. It demonstrates practical spreadsheet preparation, company detail verification, SPSS frequency tables, crosstabs, and reporting.

<img width="1600" height="900" alt="01_project_overview" src="https://github.com/user-attachments/assets/2c1dad60-b124-4740-8d9a-df77f162694e" />


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

<img width="1600" height="900" alt="02_state_frequency" src="https://github.com/user-attachments/assets/b6cba8ab-6a99-49da-a636-d15c664bed4e" />


This output summarises the distribution of job listing records across Australian states and territories.

### Company Detail Verification Status

<img width="1600" height="900" alt="03_verification_status" src="https://github.com/user-attachments/assets/537f292e-8488-4ddf-bce3-18d729d9ebe9" />


This output shows how many job listing rows have verified company details and how many still require further detail validation.

### Top Job Categories

<img width="1600" height="900" alt="04_top_categories" src="https://github.com/user-attachments/assets/76d483f3-3c72-43f9-8a06-13078d808bb7" />


This output identifies the highest-volume job categories in the dataset.

### State by Verification Status Crosstab

<img width="1600" height="900" alt="05_state_verification_crosstab" src="https://github.com/user-attachments/assets/7130a79b-ec9a-468f-b18a-9b991bb5ddef" />


This crosstab helps identify where company detail verification coverage is strongest or weakest by state.

## Cleaned Report Outputs

<img width="1600" height="900" alt="06_clean_report_outputs" src="https://github.com/user-attachments/assets/2736bca7-0532-49c5-a11c-52d3f6887980" />



## Limitations

- Not all company details have been verified.
- The dataset currently includes **827 verified rows** and **6,806 rows requiring further detail validation**.
- The analysis is descriptive and focuses on frequencies, crosstabs, verification coverage, and reporting readiness.
- The project does not use predictive modelling or inferential statistical testing.



## Summary

This project demonstrates a practical workflow for turning recruitment job listing data into a cleaned, analysable dataset and SPSS-style report. The work combines Excel-based preparation with SPSS descriptive analysis to support data quality review, company detail tracking, and reporting.
