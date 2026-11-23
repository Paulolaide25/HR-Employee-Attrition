# HR Employee Attrition: SAS Analysis

Statistical analysis of employee attrition in SAS Enterprise Guide, completed as a business data analysis group assessment (Group 102). It uses the IBM HR Analytics dataset of 1,470 employees, of whom 237 left.

## Business question
Do employees who leave the company differ in age from those who stay?

## Key findings
| | Stayed | Left |
|---|---|---|
| Employees | 1,233 | 237 |
| Mean age | 37.56 | 33.61 |
| Median age | 36 | 32 |
| Std deviation | 8.89 | 9.69 |
| 95% CI for mean age | 37.06 to 38.06 | 32.37 to 34.85 |

- **Leavers are about four years younger on average**, and the two confidence intervals do not overlap.
- The most common age among stayers is 34, against 29 among leavers.
- Employees who left are more spread out in age than those who stayed.

## Method
Descriptive statistics, `PROC MEANS` and `PROC UNIVARIATE` distribution analysis with histograms, run separately for each attrition group.

## Tools
SAS Enterprise Guide (PROC MEANS, PROC UNIVARIATE).

## Repository contents
| File | Description |
|---|---|
| `SAS ANALYSIS ASSESSMENT - GROUP 102.egp` | Enterprise Guide project with the full analysis |
| `Business Data Analysis - Assesment.egp` | Enterprise Guide project file |
| `PDF - EMPLOYEE ATTRITION.pdf` | Mean age by attrition group |
| `PDF - Distribution Analysis.pdf` | Age distribution analysis |
| `PDF - Age Attrition Distribution Analysis.pdf` | Age distribution split by attrition |

Open the `.egp` files in SAS Enterprise Guide. The PDFs show the output without needing SAS.

For a Python analysis of the same data, see [IBM-Employee-Attrition](https://github.com/Paulolaide25/IBM-Employee-Attrition).
