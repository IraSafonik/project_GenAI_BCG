# Task Instructions and Execution

## Task Overview

The task involves manually extracting key financial data for the last three fiscal years from the 10-K filings of Microsoft, Tesla, and Apple. After data collection, the analysis is performed using Python to identify trends and insights for developing an AI-powered financial chatbot.

## Step 1: Data Extraction

1. **Access SEC's EDGAR Database:**
   - Locate 10-K filings for Microsoft, Tesla, and Apple for the last three fiscal years.
<img width="798" alt="Знімок екрана 2024-05-21 о 15 56 42" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/bacfa449-bf84-4d7a-b22f-4f5ed68b3812">
<img width="1380" alt="Знімок екрана 2024-05-21 о 15 45 00" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/82a2c2c8-8398-47c2-ac24-55bdcc7d3cb0">
<img width="1341" alt="Знімок екрана 2024-05-21 о 15 43 22" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/761b078e-57ca-4580-a3aa-dec63e5772e7">
The financial statements have been extracted from SEC'S EDGARS Database: https://www.sec.gov/edgar/searchedgar/cik

2. **Manual Extraction:**
   - Extract total revenue, net income, total assets, total liabilities, and cash flow from operating activities for each company:
     
3. **Organize Data:**
   - Compile the extracted data into an Excel spreadsheet.
<img width="874" alt="Знімок екрана 2024-05-21 о 15 58 45" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/ec5321dc-a50e-4186-830d-c82b11db5749">

## Step 2: Preparing the Jupyter Notebook Environment

1. **Install and Launch Jupyter:**
   - Install Jupyter using pip:
     ```bash
     pip install notebook
     ```
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```

2. **Create a New Notebook:**
   - Create a new notebook in Jupyter for the analysis.

## Step 3: Python Analysis in Jupyter

1. **Import Pandas:**
   - Import the pandas library:
     ```python
     import pandas as pd
     ```

2. **Load Data:**
   - Convert the Excel file to CSV and load it into a pandas DataFrame:
     ```python
     df = pd.read_csv('path_to_csv_file.csv')
     ```

3. **Analyze Trends:**
   - Calculate year-over-year percentage changes for financial metrics:
     ```python
     df['Revenue Growth (%)'] = df.groupby(['Company'])['Total Revenue'].pct_change() * 100
     df['Net Income Growth (%)'] = df.groupby(['Company'])['Net Income'].pct_change() * 100
     ```
<img width="833" alt="Знімок екрана 2024-05-21 о 16 49 22" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/c0e3f0c4-bbdd-4ab8-b884-69bf63107546">

4. **Summarize Findings:**
   - Use markdown cells to document the analysis, trends, and insights.
<img width="730" alt="Знімок екрана 2024-05-21 о 16 49 31" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/dc9446de-fc7e-47f9-87f9-2de4b62086a9">

## Step 4: Documentation and Submission

1. **Document Analysis:**
   - Use markdown in Jupyter to document methodology, observations, and conclusions.

2. **Export Notebook:**
   - Export the notebook as a PDF or HTML file:
     - From the "File" menu, select "Download as" and choose the preferred format.

---

This process allows for a focused approach to analyzing financial data using pandas within Jupyter, providing a clear narrative of the financial analysis. This experience enhances skills in programmatic financial data analysis, essential for data-driven decision-making.
