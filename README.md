# End-To-End Text To SQL LLM App

This Streamlit application enables seamless conversion of natural language queries into SQL (Structured Query Language) queries, along with querying an SQLite database. Leveraging the Gemini-pro API for language model capabilities, it offers a user-friendly interface for interacting with databases using plain English queries.

## Features:
1. Natural Language Interface: 
2. Easily input queries in everyday language and let the application handle translation into SQL.
3. End-To-End Solution: From inputting text queries to fetching results from the database, this app provides a comprehensive solution.
4. Database Compatibility: Compatible with SQLite databases, ensuring easy integration and demonstration.
5. User-Friendly Interface: Intuitive design for smooth navigation and interaction.
6. Fast and Efficient: Utilizes efficient algorithms for quick conversion and retrieval of results.

## How to Use:
1. Run the Application: Execute the following command in your terminal to run the application locally:

streamlit run app.py

2. Input Text Query: Enter your query in natural language format into the provided text input field.
3. Translate: Click on the 'Translate' button to convert your text query into SQL.
4. Execute Query: Once the translation is complete, execute the SQL query to retrieve results from the connected SQLite database.
5. View Results: The results will be displayed within the application interface for easy access.

## Technologies Used:
Python: Backend server environment and application logic.
Streamlit: Web application framework for building interactive web applications.
Gemini-pro API: Leveraged for language model capabilities.
SQLite: SQL database for demonstration purposes.

## Installation:
To install and run the application locally, follow these steps:

1. Clone this repository to your local machine.
git clone https://github.com/your/repository.git

2. Install dependencies.
pip install -r requirements.txt

3. Start the application.
streamlit run app.py