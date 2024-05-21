# Project: AI-Powered Financial Chatbot from Boston Consulting Group (BCG)

## Project Overview

Welcome to the AI-Powered Financial Chatbot project! This initiative, developed by me and the GenAI consulting team at Boston Consulting Group (BCG), aims to leverage generative AI to analyze and interpret financial documents, specifically 10-K and 10-Q reports. Our goal is to build an intelligent chatbot that not only extracts and analyzes key financial data but also provides actionable insights in an interactive and user-friendly manner.

### My team at BCG
<img width="960" alt="Знімок екрана 2024-05-20 о 23 24 21" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/a3b68613-870b-4664-be7d-b2a86ed00945">

## Objective
The primary objective of this project is to create an AI-driven chatbot that can:
- Extract and Analyze Financial Data: Automatically extract key financial metrics and information from 10-K and 10-Q documents.
- Identify Significant Trends: Use data analysis techniques to identify and highlight significant trends and patterns in the financial data.
- Generate Insights: Provide insights and interpretations of the data that are useful for strategic decision-making.
- Interactive Communication: Offer an interactive platform for users to query financial information and receive understandable, detailed responses.

## Project Components
1. Data Extraction and Preparation
- Document Parsing: Utilize natural language processing (NLP) techniques to parse and extract relevant sections from 10-K and 10-Q documents.
- Data Cleaning: Ensure the extracted data is clean, structured, and ready for analysis. This involves handling missing values, normalizing data formats, and removing redundancies.
2. Data Analysis
- Trend Analysis: Apply statistical and machine learning methods to identify trends in financial metrics over time.
- Anomaly Detection: Detect any anomalies or unusual patterns that may indicate financial irregularities or areas requiring further investigation.
3. AI-Driven Insights
- Predictive Analytics: Implement models to forecast future financial performance based on historical data.
- Sentiment Analysis: Analyze the sentiment of qualitative sections of the reports (e.g., management discussions) to gauge the overall tone and potential implications for the company's future.
4. Chatbot Development
- Natural Language Understanding (NLU): Develop the chatbot's ability to understand and interpret user queries about financial data.
- Response Generation: Generate clear and concise responses, offering explanations, insights, and actionable recommendations based on the analyzed data.
- User Interaction: Design an intuitive user interface that allows seamless interaction with the chatbot.

## Specific Project Requirements and Outcomes
- Efficiency: Significantly reduce the time taken to analyze financial documents compared to traditional methods.
- Accuracy: Provide precise and reliable financial insights backed by thorough data analysis.
- User-Friendly Interface: Ensure the chatbot is intuitive and easy to use for GFC’s diverse client base, regardless of their financial expertise.
- Scalability: Ensure the solution can handle an increasing number of documents and user queries.

## Technologies Used
- Python (NumPy, Pandas, scikit-learn, PyTorch, Hugging Face)
- Streamlit (UI/UX)
- Cloud Services (AWS/GCP)

## How to Use
Setup:
Clone this repository.
Install the required dependencies using pip install -r requirements.txt.
Obtain API keys for any third-party services used (e.g., NLP libraries, sentiment analysis tools).

Running the Application:
Run the data extraction script to process the financial documents.
Execute the data analysis module to generate insights and trends.
Launch the chatbot interface and interact with it to query financial information.

Customizing:
Modify the configuration files to adjust the parameters for data extraction and analysis.
Extend the chatbot's knowledge base by adding new financial documents or adjusting the NLP models for improved accuracy.

## Task 1
1. Data extraction:
- Research and review 10-K documents.
- Focus on key financial figures and ratios.
2. Basic analysis:
- Identify significant financial trends and indicators.
- Assess the financial health and performance of the companies.
3. Data preparation:
- Format and clean the data for AI model integration.
4. Deliverable:
A comprehensive data analysis report, which should include:
- my findings
- a summary providing insights into the financial health of the analyzed companies.

## Project Execution
### Step 1: Data Collection and Preparation
- Document Gathering: Collect 10-K and 10-Q reports from GFC's database and public sources.
- Data Parsing: Utilize natural language processing (NLP) to extract relevant sections from these documents.
- Data Cleaning: Clean and structure the data by handling missing values, normalizing formats, and removing redundancies.

### Step 2: Data Extraction Techniques
#### Key Sections of 10-K Reports:
1. Income Statement:
- Key Data Points: Total revenue, cost of goods sold (COGS), operating expenses, net income.
- Extraction Technique: Focus on the income statement summary, usually in the early pages. Note year-over-year changes.
2. Balance Sheet:
- Key Data Points: Current assets, long-term assets, current liabilities, long-term liabilities, total shareholders’ equity.
- Extraction Technique: Focus on the balance sheet summary. Compare assets against liabilities to gauge financial health and note significant changes.
3. Cash Flow Statement:
- Key Data Points: Cash from operating, investing, and financing activities.
- Extraction Technique: Analyze the cash flow statement to understand cash generation and expenditure, providing insights into liquidity.
4. Effective Data Extraction Techniques:
- Manual Extraction: Manually review documents to understand their layout and locate key information.
- Highlight and Annotate: Use digital tools to highlight and annotate key figures and notes for easy reference.
- Excel and Spreadsheet Tools: Input key figures into a spreadsheet for analysis and comparison.
- Automated Extraction Tools: Use Python libraries like Beautiful Soup or Pandas to automate data extraction from digital documents.

##### Here are resource to help me:
[How to Read a 10-K/10-Q](https://www.sec.gov/oiea/investor-alerts-and-bulletins/how-read-10-k10-q)

### Step 3: Data Cleaning and Transformation
- Data Cleaning: Correct or remove incorrect, corrupted, or duplicate data. Techniques include filling in missing values, smoothing noisy data, and resolving inconsistencies.
- Data Transformation: Normalize and standardize data for consistency. Convert financial figures to a consistent format (e.g., all figures in thousands or millions) and adjust for inflation or currency changes where necessary.

### Step 4: Preprocessing for AI Models
- Feature Engineering: Use domain knowledge to create features that enhance machine learning algorithms. In financial data, this might involve creating ratios or deriving financial health indicators from raw data.
- Data Encoding and Formatting: Encode categorical data (like fiscal quarters) into numerical values and restructure data sets for time-series analysis.
- Dealing with Time-Series Data: Handle trends and seasonality carefully, integrating lag features that capture past values.

### Key Takeaways:
Preparing and preprocessing data is crucial for successfully applying AI in finance. Ensuring that the data fed into AI models is clean, consistent, and well-structured maximizes the model's ability to learn, make accurate predictions, and provide valuable insights. This stage involves both technical execution and understanding the financial context and relevance of the data being processed. By mastering these skills, financial data can be effectively prepared and preprocessed, making it ready for AI-driven applications.
