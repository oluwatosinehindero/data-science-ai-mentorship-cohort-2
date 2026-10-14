# Assignment 01 - Customer and Transaction Data Analysis

## Objective

The purpose of this assignment is to explore customer and transaction data using Python.

You are expected to clean and preprocess the datasets, investigate their structure and quality, perform exploratory data analysis and communicate the most important findings.

No machine learning model is required for this assignment.

## Datasets

Two datasets are required:

- `customers_data.csv`
- `transactions_data.csv`

The datasets were distributed privately by the mentor and are not stored in this GitHub repository.

## Dataset Loading Note

The customer dataset is tab-separated despite having a `.csv` extension.

It can be loaded using:

***customers = pd.read_csv("customers_data.csv", sep="\t")***

The transaction dataset can be loaded normally:


***transactions = pd.read_csv("transactions_data.csv")***


## Assignment Tasks
Complete the following using Python:
1. Understand the Data
- Load both datasets.
- Examine the number of rows and columns.
- Review the column names.
- Examine the data types.
- Identify the variables contained in each dataset.
- Determine how the two datasets can be related.

## Assess Data Quality
Investigate:
- missing values;
- duplicate records;
- incorrect or inconsistent data types;
- unusual values;
- possible outliers;
- inconsistent categories; and
- any other data-quality problems you identify.

## Clean and Preprocess the Data
Apply appropriate cleaning and preprocessing.
Every important decision should be explained.
Do not remove or change data simply because it looks unusual. Investigate it first and justify your decision.

## Explore the Customer Data
Investigate meaningful characteristics of the customers and their accounts.
Your analysis may include:
- account status;
- account/product types;
- account balances;
- sectors;
- card status;
- digital-channel usage;
- account-opening patterns; and
- other useful characteristics you identify.

## Explore the Transaction Data
Investigate transaction behaviour.
Your analysis may include:
- transaction frequency;
- transaction value;
- debit and credit activity;
- transaction types;
- transaction activity over time; and
- unusual transaction patterns.

## Explore Relationships Between the Datasets
Investigate how customer/account information relates to transaction behaviour.
Do not assume that every record in one dataset has a matching record in the other.
Check the relationship between the datasets before deciding how they should be combined.
Explain your joining or merging approach.

## Visualisation
Create appropriate visualisations that help communicate your findings.
Each visualisation should:
- have a clear purpose;
- contain an appropriate title;
- have labelled axes where appropriate; and
- be followed by a short interpretation.

## Findings
Identify and explain the most important insights discovered during your analysis.
Do not simply describe charts. Explain what the results mean.

## Data Protection
Do not publish personal or potentially sensitive information from the datasets.
Do not include raw values from fields such as:
- customer identifiers;
- account identifiers;
- addresses;
- email addresses;
- transaction IDs; or
- transaction narratives containing identifiable information.
Use aggregated or anonymised information when presenting findings.

## Expected Submission
Your submission should contain:
- customer_transactions_analysis.ipynb
- report.md or a PDF report
Your notebook should contain the complete analysis.
Your report should summarise the most important findings in a clear and concise way.

## Suggested Report Structure
1. Introduction :
Briefly explain the purpose of the analysis.
2. Dataset Overview :
Describe the datasets and the important variables.
3. Data Quality and Cleaning :
Summarise the main data-quality issues and how they were handled.
4. Key Findings : 
Present the most important insights supported by appropriate evidence or visualisations.
5. Conclusion : 
Summarise what you learned from the analysis.

## Submission
Submit your work through your GitHub assignment branch.
Do not commit directly to the main branch.
When your work is complete, create a Pull Request for mentor review.
