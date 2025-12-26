# 🧠 Text-to-SQL AI Assistant

A **AI-powered Text-to-SQL application** that allows users to query an SQLite database using plain English.  
The app converts natural language questions into SQL queries using **Groq LLM + LangChain**, executes them on a database, and displays the results via **Streamlit UI**.

---

## 🚀 Features

- 🔤 Convert **English questions → SQL queries**
- 🤖 Powered by **Groq LLM (LLaMA 3.3)**
- 🔗 Uses **LangChain prompt chaining**
- 🗄️ Executes queries on **SQLite database**
- 📊 Displays results in a clean **Streamlit UI**
- 🧠 No SQL knowledge required for users

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit** – UI
- **SQLite** – Database
- **LangChain**
- **Groq API** (LLaMA 3.3 model)
- **Pipenv** – Environment management

---

## 📂 Project Structure
text-to-sql/
│
├── main.py # Streamlit UI
├── student.db # SQLite database
├── Pipfile
├── Pipfile.lock
└── README.md


## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone <your-repo-url>
cd text-to-sql 
```

2️⃣ Install Dependencies (Pipenv)
``` bash 
pipenv install streamlit langchain-groq
```
3️⃣ Set Environment Variable
```bash
Groq_API_Key:"your-key"
```
4️⃣ Run the Application
```bash
pipenv run streamlit run main.py
```