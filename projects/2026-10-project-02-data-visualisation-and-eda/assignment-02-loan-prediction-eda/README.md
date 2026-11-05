# Assignment 02 - Loan Prediction Data Analysis with Python

## Objective

The purpose of this assignment is to clean, preprocess and explore the Loan Prediction datasets using Python.

Although the dataset is called a Loan Prediction dataset, the focus of this assignment is exploratory data analysis.

You are not required to build a machine-learning prediction model at this stage.

The objective is to understand the data, investigate data-quality issues, explore important relationships and communicate meaningful findings.

## Datasets

Two files are provided:

- `train.csv`
- `test.csv`

The training dataset contains the `Loan_Status` variable.

The test dataset does not contain `Loan_Status`.

Mentees should understand this difference before beginning the analysis.

## Assignment Tasks

### 1. Understand the Data

Load and inspect the datasets.

Investigate:

- number of rows and columns;
- column names;
- data types;
- categorical variables;
- numerical variables; and
- the difference between the training and test datasets.

### 2. Assess Data Quality

Investigate:

- missing values;
- duplicate records;
- incorrect or inconsistent data types;
- unusual values;
- possible outliers;
- inconsistent categories; and
- any other data-quality issues you identify.

### 3. Clean and Preprocess the Data

Apply appropriate cleaning and preprocessing.

Explain important decisions.

Do not remove observations simply because they appear unusual.

Investigate them first and justify your approach.

### 4. Explore Applicant Characteristics

Investigate relevant applicant characteristics such as:

- gender;
- marital status;
- number of dependants;
- education;
- self-employment status;
- applicant income;
- co-applicant income;
- property area; and
- other useful characteristics.

### 5. Explore Loan Characteristics

Investigate:

- loan amount;
- loan term;
- credit history;
- loan status; and
- other relevant loan characteristics.

### 6. Explore Loan Outcomes

Using the training dataset, investigate relationships between `Loan_Status` and other variables.

You may consider questions such as:

- Is credit history associated with loan approval?
- Does applicant income appear to differ between approved and rejected applications?
- Is loan approval associated with education?
- Does property area appear to matter?
- Are there differences by marital status?
- Do loan amounts differ between approved and rejected applications?
- Are there interactions or patterns worth further investigation?

Do not assume that association means causation.

### 7. Visualisation

Create appropriate visualisations to support your analysis.

Every important chart should:

- have a clear title;
- have labelled axes where appropriate;
- use an appropriate chart type; and
- be followed by an interpretation.

### 8. Findings

Identify the most important patterns discovered during the analysis.

Explain what the findings mean rather than merely describing the charts.

## Important Analytical Note

The training dataset contains the `Loan_Status` outcome and can therefore be used to investigate relationships with loan approval.

The test dataset does not contain this outcome.

Your analysis should recognise this difference.

Do not create a `Loan_Status` value for the test dataset unless specifically instructed to build a predictive model in a future assignment.

## Expected Submission

Your submission should include:

- `loan_prediction_analysis.ipynb`;
- `report.md` or a PDF findings report.

## Suggested Report Structure

### 1. Introduction

Explain the purpose of the analysis.

### 2. Dataset Overview

Describe the training and test datasets.

### 3. Data Quality

Explain the major data-quality issues identified.

### 4. Data Cleaning and Preprocessing

Explain how the data was prepared for analysis.

### 5. Key Findings

Present the most important findings supported by evidence and visualisations.

### 6. Insights

Explain the meaning and potential implications of the findings.

### 7. Conclusion

Summarise the major lessons from the analysis.

## Submission

Submit your work through your individual GitHub assignment branch.

Do not commit directly to the `main` branch.

Create a Pull Request when the assignment is ready for mentor review.
