# Financial Chatbot 
(BUILD AS A PART OF BCG GEN AI JOB SIMULATION)

## Overview
This is a simplified financial chatbot  developed to provide responses to predefined queries regarding the financial performance of Microsoft, Tesla, and Apple. The chatbot demonstrates the basics of AI-powered interaction with financial data, focusing on accuracy, clarity, and accessibility.
The main goal of this project is to introduce users to the concept of financial chatbots, showing how structured financial data can be leveraged to provide informative and interactive responses without the need for advanced AI or deep learning models.

---

## Features

- **Predefined Query Responses**: The chatbot can answer specific financial questions such as:
  - Total revenue for a company
  - Net income changes over the last year
  - Cash flow from operating activities
- **Data-Driven Responses**: Responses are based on structured financial data stored in a CSV file.
- **Command-Line Interaction**: Users can interact with the chatbot through a simple command-line interface.
- **Clear and Concise Outputs**: The chatbot provides direct answers suitable for quick financial insights.

---

## Data

- The chatbot uses a CSV file containing financial data for Microsoft, Tesla, and Apple over the last three fiscal years.
- Key metrics include:
  - Total Revenue (Billion $)
  - Net Income (Billion $)
  - Total Assets (Billion $)
  - Total Liabilities (Billion $)
  - Cash Flow from Operating Activities (Billion $)
  - Revenue Growth (%)
  - Net Income Growth (%)

---

## How It Works

1. **Data Loading**: The financial data CSV is loaded using the `pandas` library.
2. **User Input**: Users type a query into the chatbot interface.
3. **Logic Matching**: Using `if-else` statements, the chatbot matches the query to one of the predefined questions.
4. **Response Generation**: The chatbot fetches the relevant financial metric from the data and returns a formatted response.
5. **Limitations Handling**: If the query does not match any predefined questions, a default message is returned indicating the limitation.

---

## Sample Queries

- `"What is the total revenue of Microsoft?"`
- `"How has Tesla's net income changed over the last year?"`
- `"What is the cash flow from operating activities for Apple?"`

**Example Response:**

```text
The total revenue of Microsoft in 2024 is $211.91 Billion.
The net income of Tesla increased by 0.55% from 2022 to 2023.
The cash flow from operating activities of Apple in 2024 is $111.45 Billion.
```
---
## Limitations

- Can only respond to predefined queries; queries outside this set are not understood.

- No natural language processing is implemented; exact query matching is required.

- Interaction is currently limited to command-line input/output.

- Responses are static, based solely on the provided CSV data.

- Does not perform predictive analytics or real-time financial update

---
## Conclusion

Financial chatbot serves as an introductory prototype for financial chatbots, providing an interactive way to explore financial data programmatically. While simplified, it demonstrates the potential of chatbots to deliver fast, accurate, and data-driven insights in the financial domain. The project lays the foundation for more advanced AI-powered financial analysis tools in the future.

