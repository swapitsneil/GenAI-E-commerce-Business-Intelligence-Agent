# 🛒 GenAI E-Commerce Business Intelligence Agent
A fully automated, intelligence-driven BI system powered by Generative AI, SQL, analytics & conversational insights.
## 🚀 Overview

GenAI E-Commerce BI Agent is an end-to-end intelligent analytics system that combines data engineering, business intelligence and Generative AI to analyze e-commerce sales, generate insights, answer natural language queries, build visualizations, and help decision-makers take actions instantly.

This project transforms raw e-commerce data into:
✔ actionable insights
✔ auto-generated reports
✔ business KPIs
✔ conversational analytics using LLMs

## ✨ Key Features
🧠 1. GenAI-Powered Conversational Insights

Ask any business question:
"Which category performed best last quarter?"
"Predict sales for next month"
"Which regions need marketing attention?"

📊 2. Automated BI Dashboard

The system automatically generates:
- Total sales, revenue, orders
- Region-wise performance
- Monthly/Quarterly trends
- Category & product segmentation
- Forecasting results

📈 3. LLM-Generated SQL Queries

Your natural language question → LLM → optimized SQL query → result.
This eliminates manual coding and enables instant analysis.

🔍 4. Data Quality + Pre-processing Pipeline

Includes:
- Duplicate handling
- Null treatment
- Feature engineering (profit, margins, seasonal indicators, avg order value, etc.)
- Temporal segmentation

🛠 5. Fully Reproducible Jupyter Notebook

Notebook includes:
- Step-by-step workflow
- Code execution blocks
- Visualizations
- LLM response examples

## 🧩 Tech Stack
Languages
- Python
- SQL

Libraries
- Pandas
- Plotly
- Gemini API (for GenAI agent)
- SQLite

## 📁 Project Structure
GenAI-Ecommerce-BI-Agent/
│
├── ecomai.ipynb                # Main Jupyter Notebook (GenAI + AI agent)
├── ecom.ipynb                  # EDA 
├── ecomcleaned.csv             # cleaned dataset
├── README.md                   # Project documentation
└── requirements.txt

## How It Works

1. **Data Engineering** (`ecom.ipynb`)  
   → Cleaned 500K+ transactions, calculated Revenue, stored in SQLite

2. **AI Agent** (`ecomai.ipynb`)  
   → One function `ai_analyze("your question")` does everything:
   - Converts English → Accurate SQL
   - Runs query
   - Auto-generates best Plotly chart
   - Shows insights
   - Gives downloadable report

**Try these:**
python
ai_analyze("Show me monthly revenue trend")
ai_analyze("Top 5 countries by revenue in 2011")
ai_analyze("What was total sales in December 2011?")
ai_analyze("Top 10 products")

💬 Example Queries You Can Ask the Agent
"Show me top 5 products with highest profit"
"Forecast revenue for next 3 months"
"Which category is declining year-on-year?"
"Generate a pie chart of region-wise revenue"
"Give strategic recommendations for Electronics" 

## 📸 Screenshots

<img width="1676" height="966" alt="Image" src="https://github.com/user-attachments/assets/133e4311-f521-4340-908c-7207063dfc5e" />

<img width="1978" height="1170" alt="Image" src="https://github.com/user-attachments/assets/a52cc4f4-f9b6-4424-b66c-c2d796856d50" />

<img width="2404" height="1170" alt="Image" src="https://github.com/user-attachments/assets/2a7341f4-c606-429c-bb0b-cad51fc636ec" />

<img width="1680" height="878" alt="Image" src="https://github.com/user-attachments/assets/c9dbeded-4493-494d-8295-ee465ce5ebea" />

<img width="1560" height="1200" alt="Image" src="https://github.com/user-attachments/assets/05935d33-f1cd-45bf-9f1e-ce85c2048af7" />

<img width="2402" height="1184" alt="Image" src="https://github.com/user-attachments/assets/e6faece3-64e2-4aba-8774-483c39ac9cff" />

<img width="1860" height="1016" alt="Image" src="https://github.com/user-attachments/assets/365a6f90-fe9a-432d-906b-e32116f15347" />

## 🏁 Getting Started
Install requirements:

    pip install -r requirements.txt

Run notebook:

    jupyter notebook ecomai.ipynb

## 🎯 What I Learnt from This Project

Creating a full end-to-end GenAI analytics pipeline
LLM-powered SQL generation
Modern BI development
Data engineering for e-commerce
Launching a real GenAI product

## 🤝 Contributions

PRs are welcome!
Feel free to open issues & improve the agent.

## ⭐ If you like this project, give it a star!

Helps recruiters find it 🙌✨
