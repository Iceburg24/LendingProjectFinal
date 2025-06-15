**Lending Club Loan Analysis Project**
----------------------------------------------------------------------------------------------------------------
📌 Project Overview -
This project involves end-to-end data analysis and transformation on Lending Club datasets to understand borrower behavior and predict loan default risks. The project is divided into three main phases:

1)Data Ingestion & Cleaning
a)Integrated four raw CSV files: Customers, Loans, Repayment, and Defaulters.
b)Performed data quality checks: handling null values, standardizing formats, and removing duplicates.
c)Merged datasets using appropriate keys (like loan_id, member_id) to form a unified structured dataset.
d)Created permanent tables for downstream processing.

2)Data Processing & Feature Engineering
a)Derived new insights from existing columns (e.g., loan-to-income ratio, repayment duration).
b)Applied transformations and feature selection to prepare data for scoring.
c)Categorized users based on risk scores using business logic defined in Spark SQL.
d)Used PySpark for distributed and scalable data handling.

3)Scoring & Output Generation
a)Developed a scoring logic to classify borrowers into risk buckets.
b)Final processed dataset serves as input for future ML model development or dashboard visualization.

💻 Technologies Used
1)PySpark (Spark SQL & DataFrames)
2)Jupyter Notebook
3)Pandas (during initial cleanup)
4)SQL-based transformations
5)GitHub for version control

📈 Objective
To build a reliable and scalable data pipeline that cleans and transforms Lending Club data for downstream analytics—specifically for identifying high-risk borrowers and understanding loan performance patterns.
