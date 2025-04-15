# Text-to-SQL Q/A Web App 📖

## Description
This project is an interactive web application developed with **Streamlit**, allowing users to ask questions in natural language and receive answers based on a SQL Server database. The app automatically converts textual queries into valid SQL queries, executes them, and displays the results in a comprehensible format (table or raw text).

---

## Key Features
1. **Intuitive User Interface**:
   - Input area for entering questions in natural language.
   - Options to display results as a table or raw SQL query.
   - Execution button to run the query.

2. **Query Processing**:
   - Automatic conversion of textual questions into valid SQL queries.
   - Query execution on a SQL Server database.
   - Display of results in a user-friendly format (table or text).

3. **Custom Visual Design**:
   - Dark theme for an enjoyable user experience.
   - Custom CSS styles to enhance readability and aesthetics.

4. **Error Handling**:
   - Clear error messages in case of issues during query execution.
   - Loading indicator during query processing.

---

## Technologies Used
- **Streamlit**: A Python framework for quickly creating interactive web applications.
- **SQL Server**: Relational database used to store and manipulate data.
- **Python**: Main programming language used for backend development.
- **Custom CSS**: To improve the appearance of the user interface.

---

## Project Structure
The project is structured as follows:
/project-root/
│
├── app.py # Main file containing Streamlit code
├── requirements.txt # List of Python dependencies
├── README.md # This file
└── styles.css # Optional file for additional custom CSS (if necessary)



---

## Installation and Configuration
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/text-to-sql-app.git
   cd text-to-sql-app
   ```

## Install Dependencies :
   ```bash
  streamlit run app.py
   ```

## Access the Application :
   ```bash
Open your browser and navigate to: http://localhost:8501.
```


