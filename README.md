🧾 Full-Stack Expense Management System

End-to-End Data-Driven Expense Tracker built with FastAPI, Streamlit, and MySQL

🔍 Overview

This project is a full-stack expense tracking system that integrates data collection, API development, and interactive visualization to provide actionable insights on user spending.

It simulates a real-world data engineering workflow, converting raw expense data into structured storage and visual analytics — a practical foundation for future Machine Learning integration such as expense forecasting or anomaly detection.

Features

⚡ Backend (FastAPI) for secure and efficient CRUD APIs

🛢️ MySQL Database for persistent data storage

📊 Streamlit Frontend for interactive visual analytics

🎨 Plotly Charts for category-wise and time-based insights

📅 Date range filters for dynamic expense tracking

✔️ Pydantic validation, logging, and unit testing included


Learning Highlights

🔆 Building data APIs and managing backend–frontend communication

🔆 Designing database schemas for analytical applications

🔆 Implementing data validation, logging, and testing for production-grade systems

🔆 Creating interactive dashboards that translate data into actionable insights

🔆 Visualizing insights using Streamlit + Plotly

🧰 Tech Stack

Python 🐍 | FastAPI ⚡ | Streamlit 📊 | MySQL 🛢️ | Plotly 🎨 | Pydantic ✔️ | Unit Testing 🧪

📁 Folder Structure

project_resources/

│
├── backend/                 # FastAPI backend (models, routes, utils) 

├── frontend/                # Streamlit frontend app

├── tests/                   # Unit and integration test scripts
│
├── analytics_ui_demo1.png   # Dashboard demo - Pie & Bar charts

├── analytics_ui_demo2.png   # Expense summary visualization

├── app_frontend_ui.png      # Streamlit frontend preview

├── README.md                # Project documentation

└── requirements.txt         # Dependencies

⚙️ Installation & Setup
# Clone the repository
git clone https://github.com/<your-username>/expense-management-system.git
cd expense-management-system

# Install dependencies
pip install -r requirements.txt

# Run the backend (FastAPI)
uvicorn backend.main:app --reload

# Run the frontend (Streamlit)
streamlit run frontend/app_frontend_ui.py


🔮 Future Scope

🔆 Integrate Machine Learning models for expense prediction

🔆 Add User Authentication & JWT-based security

🔆 Deploy on AWS / Streamlit Cloud / Render

🔆 Extend analytics with monthly trend analysis and forecasts


🙏 Acknowledgment

A big thank you to Codebasics, Dhaval Patel, and Hemanand Vadivel for their mentorship-driven learning framework that mirrors real-world analytics and ML project pipelines.

