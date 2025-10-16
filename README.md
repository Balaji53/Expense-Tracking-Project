🧾 Full-Stack Expense Management System  
**End-to-End Data-Driven Expense Tracker built with FastAPI, Streamlit, and MySQL**

---

🔍 Overview
This project is a **complete expense tracking system** that integrates **backend APIs**, **database management**, and **interactive dashboards** to help users manage and visualize their expenses.

It simulates a **real-world data engineering and ML-ready workflow** — from data storage and processing to insight generation — forming a foundation for future **predictive modeling and analytics use cases** (e.g., spending trend prediction, budget forecasting).

---

🚀 Features
- ⚙️ **FastAPI-based backend** for efficient CRUD APIs  
- 🛢️ **MySQL database** for structured expense data management  
- 📊 **Streamlit frontend** for real-time analytics and interactive dashboards  
- 🎨 **Plotly charts** for category-wise and time-based visualizations  
- 📅 **Dynamic date range filtering** and category-level summaries  
- 🧩 **Pydantic validation**, **logging**, and **unit testing**  
- 💻 *Screen recording demo available*  

---

🧠 Learning Highlights
This project helped me strengthen:
- Designing **REST APIs** with **FastAPI**
- Building **data pipelines** ready for ML applications
- Creating **interactive dashboards** for real-time visualization
- Writing **modular, production-grade Python code** with testing and validation
- Structuring end-to-end **data systems** for analytics and automation

---

🧰 Tech Stack
**Python 🐍 | FastAPI ⚡ | Streamlit 📊 | MySQL 🛢️ | Plotly 🎨 | Pydantic ✔️ | Unit Testing 🧪**

---

📁 Folder Structure
project_resources/
│
├── backend/ # FastAPI backend
│ ├── db_helper.py # MySQL DB connection and queries
│ ├── logging_setup.py # Logging configuration
│ ├── server.py # Main FastAPI app entry point
│ └── server # API route logic & configurations
│
├── frontend/ # Streamlit frontend
│ ├── app.py # Streamlit main app
│ ├── analytics_ui.py # Expense visualization dashboard (Plotly)
│ └── add_update_ui.py # Add or update expense entries
│
├── tests/ # Unit and integration test scripts
│
├── analytics_ui_demo1.png # Dashboard preview (Pie/Bar charts)
├── analytics_ui_demo2.png # Expense summary demo
├── app_frontend_ui.png # Streamlit main app UI
│
├── README.md # Project documentation
└── requirements.txt # Dependencies

yaml
Copy code

---

## ⚙️ Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/expense-management-system.git
cd expense-management-system
2️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
3️⃣ Run the Backend (FastAPI)
bash
Copy code
cd backend
uvicorn server:app --reload
4️⃣ Run the Frontend (Streamlit)
bash
Copy code
cd ../frontend
streamlit run app.py
📺 Demo Screenshots
Dashboard	Analytics	Frontend

🔮 Future Scope
🤖 Integrate Machine Learning models for spending trend prediction

🔐 Implement User Authentication and JWT-based authorization

☁️ Deploy using AWS, Render, or Streamlit Cloud

📈 Add monthly forecasting and anomaly detection modules

🙏 Acknowledgment
A special thank you to Codebasics, Dhaval Patel, and Hemanand Vadivel for their mentorship-driven learning structure that mirrors real-world analytics and ML project environments.
