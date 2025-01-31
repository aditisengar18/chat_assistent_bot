# chat_assistent_bot
# Aditi Sengar's Chat Assistant Bot

# Link
https://chatassistentbot-aditisengar.streamlit.app/

## Overview
Aditi Sengar's Chat Assistant Bot is a simple and intuitive chat assistant that interacts with an SQLite database to answer queries related to employees, departments, and other HR-related information. It is built using Streamlit and provides real-time answers by transforming natural language queries into SQL statements. The bot responds with clear, structured information while handling errors effectively.

👨‍💻 **Developed by**: Aditi Sengar

---

## 🚀 Features
- ✅ Accepts natural language queries
- ✅ Converts queries into SQL to fetch data from an SQLite database
- ✅ Returns structured responses in real-time
- ✅ Handles errors gracefully with clear messages
- ✅ Interactive and user-friendly UI using Streamlit

---

## 🗂 Database Schema
This project uses an SQLite database with the following tables:

#### **Employees Table:**
| ID | Name      | Department   | Salary | Hire_Date   |
|----|-----------|--------------|--------|-------------|
| 1  | Alice     | Sales        | 50000  | 2021-01-15  |
| 2  | Bob       | Engineering  | 70000  | 2020-06-10  |
| 3  | Charlie   | Marketing    | 60000  | 2022-03-20  |

#### **Departments Table:**
| ID | Name       | Manager    |
|----|------------|------------|
| 1  | Sales      | Alice      |
| 2  | Engineering| Bob        |
| 3  | Marketing  | Charlie    |

---

## 🛠 Supported Queries
The assistant can handle the following queries:
- "Show me all employees in the [department] department."
- "Who is the manager of the [department] department?"
- "List all employees hired after [date]."
- "What is the total salary expense for the [department] department?"

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repository:
```bash
git clone https://github.com/aditisengar18/chat_assistent_bot.git
cd chat_assistant
