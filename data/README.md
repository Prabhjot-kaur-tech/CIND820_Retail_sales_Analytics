
# Data Folder

This folder contains the raw dataset used for the CIND820 final project.

## Raw Dataset

- `Online_Retail_Raw_Data.xlsx`

## Cleaned Datasets

The cleaned datasets are not uploaded directly because the generated CSV files are larger than GitHub's web upload limit.

The cleaned datasets can be reproduced by running:

- `notebooks/Data_Cleaning_and_Preparation.ipynb`

This notebook creates:

- `online_retail_cleaned.csv`
- `online_retail_customer_cleaned.csv`

## Cleaning Process

The cleaning process includes:

- Removing duplicate records
- Removing cancelled invoices
- Removing negative quantity records
- Removing zero or negative unit price records
- Recalculating revenue
- Creating a separate customer-level dataset by removing missing CustomerID values

The main cleaned dataset is used for revenue, product, country, and trend analysis. The customer-level cleaned dataset is used for customer behaviour analysis and RFM segmentation.
