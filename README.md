Text-to-SQL Q/A Web App 📚

📖 Overview

This project is a dynamic web application built using Streamlit, enabling users to input natural language questions and retrieve answers from a SQL Server database. The app seamlessly translates text queries into SQL, executes them, and presents results in an easy-to-read format, such as tables or plain text.



✨ Key Features





🖼️ User-Friendly Interface





Text input for natural language questions.



Options to view results as a table or raw SQL query.



"Execute" button to trigger query processing.



⚙️ Smart Query Processing





Converts natural language into valid SQL queries.



Executes queries on a SQL Server database.



Displays results in a clear, user-selected format.



🎨 Modern Design





Sleek dark theme for a pleasant experience.



Custom CSS for enhanced readability and aesthetics.



🛡️ Robust Error Handling





Informative error messages for query issues.



Loading spinner during query execution.



🛠️ Technologies Used





Streamlit 🐍: Python framework for rapid web app development.



SQL Server 🗄️: Relational database for data storage and querying.



Python 💻: Core language for backend logic.



Custom CSS 🎨: Styling for a polished UI.



📂 Project Structure

/project-root/
│
├── app.py              # Main Streamlit application file
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
└── styles.css          # Custom CSS styles (optional)



🚀 Installation & Setup





Clone the Repository

git clone https://github.com/your-username/text-to-sql-app.git
cd text-to-sql-app



Install Dependencies

pip install -r requirements.txt



Run the Application

streamlit run app.py



Access the App
Open your browser and go to:
🌐 http://localhost:8501



📝 How to Use





Enter a Question
Type a natural language question in the input field (e.g., "What is the average movie duration by genre?").



Choose Display Options
Select whether to view results as a table, raw SQL query, or both.



Run the Query
Click the 🚀 Execute button to process the query.



View Results
Results will appear as a table or text based on your selection.



🖼️ Screenshot

