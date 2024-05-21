## Task Instructions and Execution

### Task Overview
The task involved manually extracting key financial data for the last three fiscal years from the 10-K filings of Microsoft, Tesla, and Apple. After data collection, I analyzed this data using Python to identify trends and insights for developing an AI-powered financial chatbot.

### Step 1: Data Extraction
1. Access SEC's EDGAR Database:
- Located 10-K filings for Microsoft, Tesla, and Apple for the last three fiscal years.
2. Manual Extraction:
- Extracted total revenue, net income, total assets, total liabilities, and cash flow from operating activities for each company.
3. Organize Data:
- Compiled the extracted data into an Excel spreadsheet.

### Step 2: Preparing the Jupyter Notebook Environment
- Install and Launch Jupyter:
- Created a new notebook in Jupyter for the analysis.

### Step 3: Python Analysis in Jupyter
- Imported the pandas library:
import pandas as pd
- Load Data:
Converted the Excel file to CSV and loaded it into a pandas DataFrame:
python
Копіювати код
df = pd.read_csv('path_to_your_csv_file.csv')
Analyze Trends:

Calculated year-over-year percentage changes for financial metrics:
python
Копіювати код
df['Revenue Growth (%)'] = df.groupby(['Company'])['Total Revenue'].pct_change() * 100
df['Net Income Growth (%)'] = df.groupby(['Company'])['Net Income'].pct_change() * 100
Summarize Findings:

Used markdown cells to document the analysis, trends, and insights.
Step 4: Documentation and Submission
Document Analysis:

Used markdown in Jupyter to document methodology, observations, and conclusions.
Export Notebook:

Exported the notebook as a PDF or HTML file:
From the "File" menu, selected "Download as" and chose the preferred format.
This process allowed me to focus on core analytical aspects using pandas within Jupyter, providing a clear narrative of the financial analysis. This experience enhanced my skills in programmatic financial data analysis, essential for data-driven decision-making.
