# 🏥 Insurance Premium Prediction API

A Machine Learning–powered REST API built using **FastAPI** to predict insurance premiums based on user details such as age, BMI, number of children, smoking habits, and region.

This project demonstrates how to integrate a trained ML model with a modern backend framework and expose it as an API.

---

## 🚀 Features
- Predicts insurance premium using a trained ML model
- Fast and lightweight backend using FastAPI
- Request validation using Pydantic
- Auto-generated API documentation (Swagger & ReDoc)
- Clean and modular code structure

---

## 🧠 Tech Stack
- Python 3.10+
- FastAPI
- Pydantic
- Uvicorn
- Scikit-learn
- NumPy
- Pandas

---

## 📁 Project Structure
insurance_premium_API/
│
├── app/
│ ├── main.py # FastAPI application entry point
│ ├── schema.py # Pydantic request/response models
│ ├── predictor.py # ML prediction logic
│ └── model/ # Trained machine learning model
│
├── requirements.txt
├── README.md
└── .gitignore

---
## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Rahuljoshi1216/insurance_premium_API.git
cd insurance_premium_API
```

## Create and activate a virtual environment
python -m venv venv

## Windows
venv\Scripts\activate

## Linux / macOS
source venv/bin/activate

## Install dependencies
pip install -r requirements.txt

## Run the Application
uvicorn app.main:app --reload
