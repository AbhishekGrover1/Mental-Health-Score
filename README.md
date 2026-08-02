<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=34&duration=3000&pause=1000&color=7C3AED&center=true&vCenter=true&width=950&lines=🧠+Mental+Health+Scorer;End-to-End+Machine+Learning;Python+%7C+Scikit-learn+%7C+FastAPI" />

<br>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)
![Joblib](https://img.shields.io/badge/Joblib-4B8BBE?style=flat-square)
![MIT](https://img.shields.io/badge/License-MIT-181717?style=flat-square)

*A production-oriented machine learning application for estimating student mental health scores from lifestyle, academic, and digital behavior indicators.*

</div>

---

# Overview

Mental Health Scorer is an end-to-end machine learning application designed to estimate a student's mental health score using structured lifestyle, academic, and social media usage attributes. The project combines a Scikit-learn prediction pipeline with a FastAPI backend to provide fast, reliable, and real-time inference through a RESTful API.

---

# Architecture

```text
               Student Input
                     │
                     ▼
          Input Validation (Pydantic)
                     │
                     ▼
           Feature Processing (Pandas)
                     │
                     ▼
      Trained ML Model (Scikit-learn)
                     │
                     ▼
      Model Loading (Joblib)
                     │
                     ▼
          FastAPI Prediction API
                     │
                     ▼
        Predicted Mental Health Score
```

---

# Key Features

- End-to-end machine learning workflow
- Production-ready REST API using FastAPI
- Robust request validation with Pydantic
- Efficient model serialization through Joblib
- Modular project architecture
- Lightweight frontend for prediction requests

---

# Technology Stack

| Layer | Technology |
|--------|------------|
| Language | Python |
| Machine Learning | Scikit-learn |
| Backend | FastAPI |
| Data Processing | Pandas |
| Validation | Pydantic |
| Serialization | Joblib |

---

# Project Structure

```text
Mental-Health-Score
│
├── assets/
├── main.py
├── Mental_Health_Model.pkl
├── ML_Project.ipynb
├── index.html
├── style.css
├── script.js
├── requirements.txt
└── README.md
```

---

# Quick Start

```bash
git clone https://github.com/AbhishekGrover1/Mental-Health-Score.git

cd Mental-Health-Score

pip install -r requirements.txt

uvicorn main:app --reload
```

API Documentation

```
http://127.0.0.1:8000/docs
```

---

# Dataset

The model is trained using the **Student Social Media and Mental Health Impact** dataset included in this repository.

---

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AbhishekGrover1)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-grover07/)

<sub>Engineered with Python, FastAPI, and Scikit-learn.</sub>

</div>
