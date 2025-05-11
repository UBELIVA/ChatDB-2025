# ChatDB-2025
ChatDB is a natural language interface system that leverages large language models to translate user queries into SQL or MongoDB commands and return the corresponding results.

## Features

- Natural language queries to MySQL and MongoDB
- SQL: supports SELECT, JOIN, WHERE, GROUP BY, ORDER BY, etc.
- MongoDB: supports $match, $group, $sort, $lookup, etc.
- Interactive execution via Jupyter Notebook
- Three real-world datasets: customers database, orders database, product database.

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
4. Set up MySQL and MongoDB databases with the datasets in the 'datasets/' folder.
5. Open the project in Jupyter notebook.
6. Open `ChatDB.ipynb` and follow the step-by-step cells.

## API Key
To use the OpenAI API:
- Open 'ChatDB.ipynb'
- Go to the cell where OpenAI is initialized
- Add your API key on the indicated line:

python
# Add your API key below
openai.api_key = " " # Replace your LLM API

## Usage

1. Open the Notebook: 'ChatDB.ipynb'
2. Run the notebook step by step
3. Enter queries like:
- "List the top 5 most sold products."
- "Show all users who purchased in 2023."

## Team

- Shuohang Wu – SQL backend, database design, GPT integration
- Chuanyu Ma – MongoDB backend, frontend design, optimization


