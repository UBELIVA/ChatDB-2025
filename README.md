# ChatDB-2025
ChatDB is a natural language interface system that leverages large language models to translate user queries into SQL or MongoDB commands and return the corresponding results.

## Features

- Natural language queries to MySQL and MongoDB
- SQL: supports SELECT, JOIN, WHERE, GROUP BY, ORDER BY, etc.
- MongoDB: supports $match, $group, $sort, $lookup, etc.
- Interactive execution via Jupyter Notebook
- Three real-world datasets: Grocery Sales, Online Shop, Social Media

## Prerequisites

- Python 3.9+
- Jupyter Notebook
- MySQL server
- MongoDB server
- OpenAI API key

## Installation

1. Clone this repository
2. [Optional] Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
3. Install dependencies:
   pip install -r requirements.txt
4. Set up MySQL and MongoDB databases with the datasets in the `datasets/` folder.
5. Add your OpenAI API key to a '.env' file (see below).
6. Open and run 'ChatDB.ipynb' in Jupyter Notebook.

## API Key Setup
Create a file named '.env' in the project root:
  **OPENAI_API_KEY=your_api_key_here**


Make sure to add '.env' to '.gitignore' to avoid uploading it to GitHub.

## Usage

1. Open the Notebook: 'jupyter notebook ChatDB.ipynb'
2. Run the notebook step by step
3. Enter queries like:
- "List the top 5 most sold products."
- "Show all users who purchased in 2023."

## Team

- Chuanyu Ma – SQL backend, database design, GPT integration
- Shuohang Wu – MongoDB backend, frontend design, optimization


