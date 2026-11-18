# Healthcare_Operations_Dashboard
An interactive Power BI dashboard analysing healthcare operations, encounter costs, payer coverage and procedure utilisation.
## Project Overview

This project involved developing an interactive healthcare operations and financial intelligence dashboard using Microsoft Power BI.

The objective was to analyse healthcare encounter activity, claim costs, payer coverage and procedure patterns to support operational monitoring and evidence-based decision-making.

## Business Problem

Healthcare organisations need reliable information about service utilisation, financial exposure, payer contributions and procedure patterns. This project explores how structured data analysis and interactive reporting can help decision-makers monitor these areas and identify opportunities for operational improvement.

## Data Source and Attribution

The datasets used in this project were provided through the **AnalystLab Africa Experience Lab Internship Programme, Week 3 assignment: Hospital Operations, Cost & Patient Flow Intelligence**.

The healthcare dataset pack included:

- `encounters.csv`
- `patients.csv`
- `procedures.csv`
- `payers.csv`
- `organizations.csv`
- `data_dictionary.csv`

**Attribution:** Healthcare dataset pack provided by AnalystLab Africa for its Week 3 internship assignment.

The analysis and dashboard were independently developed as part of the internship project. The source files have not been reproduced in this repository.

## Tools and Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data modelling and data-quality assessment

## Dataset Overview

| Dataset | Records |
|---|---:|
| Encounters | 27,891 |
| Patients | 974 |
| Procedures | 47,701 |
| Payers | 10 |
| Organizations | 1 |
| Data Dictionary | 66 |

## Data Preparation and Modelling

The preparation process included:

- Reviewing source table structures and data types.
- Assessing missing values and data completeness.
- Checking unique identifier columns for duplicate values.
- Reviewing date fields and calculating encounter durations.
- Creating relationships between Patients, Encounters, Procedures, Payers and Organizations.
- Keeping the Data Dictionary as a reference table.

## Key Dashboard Metrics

- Total Encounters
- Total Claim Costs
- Total Payer Coverage
- Encounters with Zero Recorded Payer Coverage
- Encounters Exceeding 24 Hours
- Average Claim Cost
- Procedure Frequency
- Average Procedure Base Cost

## Key Findings

- Total claim costs were approximately **$101.51 million**.
- Total recorded payer coverage was approximately **$31.10 million**.
- **13,586 encounters** had zero recorded payer coverage.
- **75 encounters** exceeded 24 hours among encounters with valid duration calculations.
- Encounter and procedure reason fields had substantial missingness, limiting some analyses.

These findings should be interpreted in the context of the dataset's completeness and documented limitations. Zero recorded payer coverage should not automatically be interpreted as an uninsured patient or an unpaid claim.

## Validation

Three important calculations were independently checked against Excel:

- Total Claim Costs
- Total Payer Coverage
- Zero Payer Coverage Encounters

Date, encounter-class and payer filters were also tested to confirm that dashboard visuals responded to user selections.

## Recommendations

1. Improve the completeness of encounter and procedure reason documentation.
2. Investigate unusually long recorded encounter durations and determine whether they reflect genuine operational events or data-quality issues.
3. Review encounters with zero recorded payer coverage to understand the underlying billing and coverage circumstances.

## Project Limitations

- The 2022 reporting period covers only January and February and should not be compared directly with complete years.
- Missing reason codes and descriptions limit the interpretation of some records.
- Some calculated encounter durations were unusually long and require further investigation.
- Zero recorded payer coverage does not necessarily indicate an absence of insurance or an unpaid claim.

## Project Deliverables

This repository includes:

- Power BI dashboard.
- Data model visual.
- Project documentation.
- Data-quality assessment.
- KPI definitions.
- Validation evidence.
- Executive summary and recommendations.

## Learning Outcomes

This project strengthened my practical experience in data preparation, data modelling, DAX calculations, Power BI dashboard development, data validation and translating analytical findings into business recommendations.
