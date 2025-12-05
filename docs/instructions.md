# Data Submission Instructions

This guide explains how to correctly complete and validate your dataset before submitting it through the **QC App**.

---

## 1. Download the Template

Get the official file from:

`templates/`

---

## 2. Review Variable Definitions

See the data dictionary for each template in `templates/` for:
- Variable names (must match exactly)
- Description
- Type (integer, float, date, categorical, string, etc.)
- Allowed values
- Required/nullable status

---

## 3. Fill in Your Data

- One row per participant/observation.  
- Keep column names and order exactly as in the template.  
- Categorical values: match allowed codes  
- Missing values: leave blank or use `NA`  
- Save as `.xlsx` or `.csv`. Do **not** use formulas or additional formatting.

---

## 4. Validate Your File

- Ensure required variables are filled  
- Confirm column names match the template's data dictionary  
- Remove extra spaces and merged cells  

---

## 5. Submit

1. Log in to **QC App** [here](https://gp2-clinical-qc-dot-gp2-data-explorer.uc.r.appspot.com/)  
2. Upload your completed `.xlsx` or `.csv` file  
3. Wait for automated validation feedback and QC steps

Note: As of December 2025, the app is under development and does not currently accommodate all data modalities. If you are submitting data that the app does not support, contact clinicaldata@gp2.org for instructions on how to submit clinical data. Please include the name of your cohort/study, the project/interest group you would like to contribute data to, and what data you would like to share. A member of the clinical data management team will walk you through the steps to deposit data for QC and inclusion in GP2 research projects. 

---

## 6. Data Privacy

- Remove all PII  
- Follow institutional and GP2 guidelines  

---

## 7. Common Formatting Errors

| Error | How to Fix |
|-------|------------|
| Column names changed | Restore names to match the template's data dictionary |
| Extra spaces | Trim spaces in column names and values |
| Categorical values not allowed | Use allowed codes found in the data dictionary |
| Merged cells | Unmerge all cells |
| Formulas instead of values | Copy and paste as values |
| Missing required variables | Fill in all mandatory fields or `NA` |
| Incorrect file type | Save as `.xlsx` or `.csv` |
