                              QueryCraft : Text-to-SQL 

Overview
QueryCraft is a web application that converts natural language questions into SQL queries using Google’s Gemini model. It allows users to generate database queries by simply typing questions in plain English, making database interaction easier for non-technical users.

Problem Statement
Many users such as managers, analysts, and students work with data stored in databases but lack knowledge of SQL. This creates dependency on developers and slows down data access. QueryCraft provides a simple solution by translating natural language queries into SQL automatically.

Objective
To develop a web-based application that allows users to input natural language queries and automatically generate SQL queries using Google Gemini AI.

Technologies Used
•	Python
•	Streamlit
•	Google Gemini API
•	dotenv
•	Git and GitHub

Key Features
•	Convert natural language to SQL queries
•	Simple and user-friendly interface
•	Secure API key management using .env
•	Real-time SQL generation
•	Lightweight Streamlit web application

Project Structure
querycraft-text2sql-using-gemini
│
├── app.py
├── requirements.txt
├── image/
├── .env
├── .gitignore
├── README.md

Advantages
•	No SQL knowledge required
•	Saves time in query writing
•	Improves data accessibility
•	Helps students learn SQL structure
•	Simple web-based interface
•	Real-time query generation
•	Works across multiple domains such as HR, sales, and education

Limitations
•	Accuracy depends on Gemini model interpretation
•	Queries are not executed without connecting to a database
•	Complex database schemas may require additional context
•	Internet connection is required for API access
•	Ambiguous queries may generate incorrect SQL

Conclusion
QueryCraft simplifies database querying by using Generative AI to convert natural language into SQL, making data access easier for users without SQL knowledge.

