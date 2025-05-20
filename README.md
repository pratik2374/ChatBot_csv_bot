# 📊 Data Analysis Chatbot

This is a Streamlit-based interactive chatbot that allows you to ask questions about your CSV data and get instant insights using LlamaIndex and Pandas.

## Features
- Chat interface for querying your CSV data
- Responses appear with a typing animation for a better user experience
- Secure API key management using Streamlit secrets
- Persistent chat history during your session

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Prepare Your Data
- Place your CSV file in the `data/` directory.
- By default, the app expects a file named `Balaji Fast Food Sales.csv` in the `data/` folder.

### 4. Set Up API Key
Create a file at `.streamlit/secrets.toml` with the following content:
```toml
[openai]
api_key = "your-openai-api-key"
```
**Note:** Never share or commit your API key publicly.

### 5. Run the App
```bash
streamlit run app.py
```
The app will open in your default web browser.

## Deployment
- For Streamlit Cloud, add your secrets in the app settings under the "Secrets" section using the same format as above.
- Make sure `.streamlit/secrets.toml` is in your `.gitignore`.

## File Structure
```
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
├── .streamlit/
│   └── secrets.toml
├── data/
│   └── Balaji Fast Food Sales.csv
└── storage/
```

## Customization
- To use a different CSV file, update the filename in `app.py` or rename your file accordingly.
- You can adjust the chat appearance and typing speed in the code.

## License
MIT 