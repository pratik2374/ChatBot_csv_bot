# Sales Data Chat Assistant

A Streamlit application that allows you to chat with your sales data using natural language queries. The application uses LlamaIndex and OpenAI's GPT model to understand and answer questions about your sales data.

## Features

- Upload and analyze CSV sales data
- Natural language querying of your data
- Support for various types of queries:
  - Specific column analysis
  - Row filtering
  - Aggregations (sum, min, max)
  - Date-based queries
  - Category-based analysis
  - And more!

## Setup

1. Install the required dependencies:
```bash
pip install -r requirements.txt
```

2. Get your OpenAI API key from [OpenAI's website](https://platform.openai.com/api-keys)

3. Run the application:
```bash
streamlit run app.py
```

## Usage

1. Enter your OpenAI API key in the sidebar
2. Upload your sales data CSV file
3. Wait for the index to be created
4. Start asking questions about your data in natural language

## Example Queries

- "What is the total sales for product X?"
- "Show me the maximum sales amount"
- "What are the top 5 products by sales?"
- "What is the average sales per region?"
- "Show me sales data for specific dates"
- "What is the sum of sales for category Y?"

## Note

Make sure your CSV file has clear column headers and is properly formatted. The application works best with structured sales data that includes columns for products, sales amounts, dates, and categories. 