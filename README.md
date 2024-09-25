QueryCraft
QueryCraft is a Streamlit application that utilizes Google Gemini's language model to convert natural language queries into SQL commands. This project is built using Python, Streamlit, and the Google Gemini API. The QueryCraft app can be accessed here

Table Structure
The app uses a predefined table "students" stored in the "student.db" file with the following structure:


How It Works
Input Query: Users enter natural language questions, e.g., "Sort the students."
Google Gemini Translation: The app utilizes Google Gemini's language model to translate the query into a SQL command.
SQL Query Execution: The translated SQL query is executed on the pre-built table stored in "sql.py."
Result Presentation: The app dynamically displays the query results, providing an interactive demonstration of natural language to SQL conversion.
Note: If the input does not result in a valid SQL query, the app responds with "Enter valid input" to guide users towards proper query formulation.