<img width="731" alt="Знімок екрана 2024-06-01 о 12 48 46" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/419e89a8-3b02-46fb-85b2-09d051cc1c7f">

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
- Python (Pandas)
- Natural Language Processing (NLP)
- Machine Learning Models
- Chatbot Development Frameworks (e.g., TensorFlow, PyTorch)
- Integrated Development Environments (IDEs) (e.g., Jupyter Notebook, VS Code)

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

## Task 2
- Develop an AI chatbot that can analyze financial data and provide insights.
- Integrate the previously extracted and analyzed data into the chatbot system.
- Test the chatbot to ensure it can effectively communicate financial performance insights and comparisons.

### Project Execution Overview

#### Principles of AI Chatbot Development
- **Rule-based Logic**
Start with rule-based responses using "if-then" logic to handle frequently asked questions about financial data.
- **State Management**
Maintain the conversation context to provide relevant and personalized responses.
- **Error Handling**
Ensure the chatbot gracefully handles unrecognized queries and guides users to appropriate questions.

#### Integrating Financial Data
- **Data Structuring**
Organize financial data in JSON or CSV formats for easy access and interpretation.
- **Retrieval Methods**
Implement methods to fetch the right data based on user queries, such as net income or revenue.
- **Predefined Data Points**
Map specific queries to predefined data points for straightforward data fetching and presentation.

#### Communicating Financial Insights
- **Simplification and Summarization**
Use clear, jargon-free language to simplify and summarize financial insights.
- **Interactive Dialogue Design**
Design dialogues to be interactive, encouraging exploration and follow-up questions.
- **Visual Aids**
Describe potential data visualizations, such as charts or graphs, to help users understand complex data.

### Ready to Develop

#### Team Roles
- **My Focus:** Implement rule-based logic for initial query responses.
- **NLP Experts:** Enhance language understanding.
- **Machine Learning Engineers:** Incorporate learning algorithms for improved responses.
- **Data Integration Specialists:** Ensure real-time data access.
- **UX Designers:** Create intuitive and user-friendly interfaces.

By following these principles and collaborating with my team, I'll develop a chatbot that effectively communicates financial data, enhancing user understanding and decision-making.

## Demonstration and Documentation
**Brief Documentation** - summary explaining how **AI Financial chatbot** works.
<img width="589" alt="Знімок екрана 2024-06-01 о 12 07 53" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/dc7832f9-0258-46f3-8af7-504bb21f8dc3">
<img width="566" alt="Знімок екрана 2024-06-01 о 12 08 02" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/29be5462-8a21-46f7-8298-4187d775fb04">
<img width="625" alt="Знімок екрана 2024-06-01 о 12 08 10" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/affba0f6-3ddf-4491-a410-9143912821d6">

### Skill gained after completing this project - BCG GenAI Job Simulation on Forage - Jun 2024.
- Completed a job simulation involving AI-powered financial chatbot development for BCG's GenAI Consulting team.
- Gained experience in Python programming, including the use of libraries such as pandas for data manipulation.
- Integrated and interpreted complex financial data from 10-K and 10-Q reports, employing rule-based logic to create a chatbot that provides user-friendly financial insights and analysis.
<img width="746" alt="Знімок екрана 2024-06-01 о 12 31 59" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/bf8581f4-9632-4617-8e50-41136f68d59f">
