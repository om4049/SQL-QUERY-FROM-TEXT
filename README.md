# Text-to-SQL LLM Application

## Description  
This project implements a natural-language to SQL application. Users enter questions in plain English, the system uses a Large Language Model to translate into SQL, executes the SQL against a database, and returns the result.

## Features  
- Accepts user input in natural language (e.g., “What were the total sales by product last quarter?”)  
- Uses the `google-generativeai` SDK to translate text into a SQL query  
- Executes the SQL query against a sample database and returns results in human-readable form  
- Easy to extend: you can adapt the schema, add more tables, or switch databases  

