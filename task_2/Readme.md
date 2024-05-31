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
   - Select 3 to 5 common financial queries (e.g., "What is the total revenue?", "How has net income changed over the last year?").
2. **Prepare Responses**
   - Use the analyzed financial data to create canned responses for these queries. This step involves mapping each predefined query to a specific response based on my data analysis.

## Step 3: Basic Chatbot Development

1. **Chatbot Logic**
   - Write a simple Python script that uses if-else statements to match user input (the predefined queries) to the responses you prepared. For a more interactive experience, consider using a basic Python library such as `input()` for command-line interaction or a simple Flask app for web-based interaction.

```python
def simple_chatbot(user_query):
    if user_query == "What is the total revenue?":
        return "The total revenue is [amount]."
    elif user_query == "How has net income changed over the last year?":
        return "The net income has [increased/decreased] by [amount] over the last year."
    # Add more conditions for other predefined queries
    else:
        return "Sorry, I can only provide information on predefined queries."
```
## Step 3: Demonstration and Documentation

1. **Test Chatbot**
Spend a few minutes testing the chatbot with the predefined queries to ensure it responds correctly.

2. **Prepare Brief Documentation**
Write a short summary explaining how my chatbot works, the predefined queries it can respond to, and any limitations.
