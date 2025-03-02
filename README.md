# Expense Management System

The Expense Management System is a web-based application designed to help users efficiently manage their personal or business finances.This Python project features a Streamlit-based frontend and a FastAPI-powered backend.


## Project Structure

- 📂 **frontend/** – Houses the Streamlit application code.  
- 📂 **backend/** – Contains the FastAPI backend server implementation.  
- 🧪 **tests/** – Includes test cases for both frontend and backend.  
- 📄 **requirements.txt** – Specifies the necessary Python dependencies.  
- 📘 **README.md** – Provides an overview and setup instructions for the project.


## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/expense-management-system.git
   cd expense-management-system
   ```
1. **Install dependencies:**:   
   ```commandline
    pip install -r requirements.txt
   ```
1. **Setting Up the MySQL Database**:
   - Create a database named `expense_tracker`.  
   - Update the database credentials in the `config.py` file.  
   - Run the provided SQL scripts (if available) to initialize the database schema.  
1. **Run the FastAPI server:**:   
   ```commandline
    uvicorn server.server:app --reload
   ```
1. **Run the Streamlit app:**:   
   ```commandline
    streamlit run frontend/app.py
   ```
