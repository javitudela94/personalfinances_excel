# personalfinances_excel
Project developed in excel in which i try to analyse and implement a dashboard to see how personal finances impact our lives.

# Project Description
This project is a personal finance tracker built in Excel to better understand and manage my bank transactions. It transforms raw banking data into clear insights through data cleaning, analysis, and an interactive dashboard.

# What It Does
Cleans and organizes banking data for consistency and accuracy.
Provides a clear view of spending patterns, income, and cash flow through descriptive analysis.
Features a dashboard to make financial insights easy to read and act on.
Includes a short report summarizing the key findings and trends.
It’s a simple yet powerful tool to take control of personal finances and plan smarter.

# Methodology
Data Extraction: Bank transactions were manually extracted from the banking app and categorized based on the "Categories" tab.
Manual Entry: Data was manually input into the file. While consistent with actual transactions, it may contain minor errors.
Data Storage: All compiled data is stored in the "FINANZAS" tab for further analysis and visualization.
A copy of the data was done to save the raw data and it is called "raw data"

# Steps
1. Data were observed carefully, searching for inconsistencie or blanks.
2. ETL: (Extract, Transformed & Load)  Data through Power Query to add minor detailed columns
     Creation of Year & Month Columns (dates) with formulas
     Create Dynamic Tables
3. Filling gaps asking for real information. Other info missed were deleted.
   
   
4. Description Analysis
     Excel formulas were used to built the report building (net income, net expenses and net investment, and           accumulated_balance, used later in the report dashboard to build the final tables and columns).
   
6. Create Dashboard replicating the information of the tables with the most important information available.
        Dashboard contains 3 different tabs. Each tab has resumee table, different graphs explaining situation of the personal finances. 
          Ingresos --> coloured in green.  Gains
             Gastos --> coloured in red. Loses
                  Ahorro  --> coloured in grey. Gains - Loses

