# BCG GenAI Financial Chatbot Internship

## Overview

This repository documents the work done as part of a virtual internship with BCG GenAI Consulting. The primary goal of the internship is to develop an AI-powered financial chatbot that can analyze and provide insights on corporate financial performance, particularly using data from 10-K and 10-Q reports. The project aims to assist Global Finance Corp. (GFC) in enhancing its financial analysis capabilities by leveraging AI to transform raw financial data into actionable insights.

## Task 1: Data Extraction and Initial Analysis

### Steps:

1. **Data Extraction:**
   - Access the SEC's EDGAR database to retrieve the 10-K filings for Microsoft, Tesla, and Apple for the last three fiscal years.
   - Extract key financial figures, including Total Revenue, Net Income, Total Assets, Total Liabilities, and Cash Flow from Operating Activities.
   - Organize the extracted data into an Excel spreadsheet for easy reference during the analysis phase.

2. **Preparing the Jupyter Notebook Environment:**
   - Install and set up Jupyter Notebook for the analysis.
   - Create a new notebook to document the analysis process.

3. **Python Analysis in Jupyter:**
   - Import necessary libraries and load the financial data into a pandas DataFrame.
   - Perform trend analysis, focusing on year-over-year percentage changes for each financial metric.
   - Explore other aggregate functions and groupings to analyze the data across different dimensions, such as by company and over the years.

4. **Documentation and Submission:**
   - Thoroughly document the methodology, observations, and conclusions within the Jupyter Notebook using markdown cells.
   - Export the completed notebook as a PDF or HTML file for submission.

## Task 2: Developing the AI-Powered Financial Chatbot

### Steps:

1. **Defining the Chatbot's Objective:**
   - Develop a chatbot designed to respond to user queries about key financial metrics such as net income and revenue growth, using the data extracted in Task 1.

2. **Implementing Rule-Based Logic:**
   - Create a framework where the chatbot uses predefined rules to map user queries to appropriate financial insights. The chatbot's responses should be clear, concise, and informative.

3. **Data Structuring and Retrieval:**
   - Organize the financial data in a structured format to facilitate easy retrieval. The chatbot should be able to access this structured data to provide accurate responses based on user queries.

4. **Communicating Financial Insights:**
   - Focus on crafting responses that simplify complex financial data into understandable insights. Consider enhancing the chatbot's interactivity by suggesting related queries or offering additional information based on user interest.

## Conclusion

This internship project has successfully laid the groundwork for developing a comprehensive AI-powered financial chatbot. The completed tasks include data extraction and analysis, as well as the implementation of basic rule-based logic to facilitate user interaction with financial data.

## Future Work

- **Enhancing NLP Capabilities:** Future iterations could incorporate natural language processing (NLP) features to enable the chatbot to understand and respond to a broader range of user queries with greater accuracy.
- **Dynamic Data Retrieval:** Integrating real-time financial databases or APIs will allow the chatbot to provide up-to-date financial insights, enhancing its value to users.
- **Machine Learning Integration:** The addition of machine learning models could enable the chatbot to offer predictive insights and more sophisticated financial analysis.
- **User Interface Development:** A user-friendly interface would make the chatbot more accessible to a wider audience, regardless of their financial expertise, ensuring a seamless user experience.

