# Project Instructions and Execution

## Chatbot Prototype

Building a fully functional AI chatbot for financial analysis is a complex process involving advanced programming and deep learning techniques. This streamlined version introduces the basics of chatbot development, focusing on creating a prototype that responds to predefined financial queries. 

## Step 1: Preparation

1. **Review the Analyzed Data**
   - Quickly review the financial data I analyzed in Task 1 to refresh my memory on what information is available.
2. **Set Up Your Environment**
   - Ensure Python and essential libraries (like pandas for data handling and Flask for a simple web application) are installed.

## Step 2: Chatbot Design and Data Preparation

1. **Define Predefined Queries**
   - Select 10 common financial queries (e.g., \n1. 'revenue growth,%', \n2. 'net income growth,%', \n3. 'assets growth,%', \n4. 'liabilities growth,%', \n5. 'cash flow from operations,%', \n6. 'total revenue', \n7. 'net income', \n8. 'total assets', \n9. 'total liabilities', \n10. 'cash flow from operations').
2. **Prepare Responses**
   - Use the analyzed financial data to create canned responses for these queries. This step involves mapping each predefined query to a specific response based on my data analysis.

## Step 3: Basic Chatbot Development

1. **Chatbot Logic**
   - Write Python script that uses if-else statements to match user input (the predefined queries) to the responses you prepared. For a more interactive experience, consider using Python library such as `input()` for command-line interaction.

```python
def financial_chatbot(query, company, year=None):
    # Responses for different queries for final_report
    final_report_responses = {
        'revenue growth,%': f"The revenue growth for {company} was {final_report[final_report['Company'] == company]['Revenue Growth (%)'].values[0]}%.",
        ...   }
# Responses for different queries for financial_report
    if year:
        financial_report_responses = {
            'total revenue': f"The total revenue for {company} in {year} was {financial_report[(financial_report['Company'] == company) & (financial_report['Year'] == year)]['Total Revenue'].values[0]}.",
             }
    else:
        financial_report_responses = {}

    # Combine both dictionaries
    responses = {**final_report_responses, **financial_report_responses}

    # Check if the user query is in the responses dictionary
    if query in responses:
        return responses[query]
    else:
        return "Sorry, I can only provide information on predefined queries."
```

## Step 3: Demonstration and Documentation

1. **Test Chatbot**
Testing the chatbot with the predefined queries to ensure it responds correctly.
<img width="534" alt="Знімок екрана 2024-06-01 о 11 49 45" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/40437e07-6746-4b40-bf28-4972962432f5">

2. **Prepare Brief Documentation**
Write a short summary explaining how my chatbot works, the predefined queries it can respond to, and any limitations.
<img width="589" alt="Знімок екрана 2024-06-01 о 12 07 53" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/dc7832f9-0258-46f3-8af7-504bb21f8dc3">
<img width="566" alt="Знімок екрана 2024-06-01 о 12 08 02" src="https://github.com/IraSafonik/project_GenAI_BCG/assets/32171563/29be5462-8a21-46f7-8298-4187d775fb04">
