<div align="center">

# 🧠 Stroke Prediction Analysis & Web App

**An End-to-End Machine Learning Project to Predict Stroke Probability**

<br />

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter Notebook" />
<img src="https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn" />
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white" alt="Streamlit" />

<br />

---

## 📖 Project Overview

Stroke is a leading cause of death and disability globally. This project aims to build an end-to-end Machine Learning pipeline to predict whether a patient is likely to get a stroke based on various health parameters like gender, age, medical conditions, and smoking status. 

The project goes beyond just data analysis and model training; it includes deploying the best-performing model (`.pkl` file) via an interactive **Streamlit Web Application**, allowing users to input medical data and get real-time stroke predictions.

---

## ✨ Key Features

- **Exploratory Data Analysis (EDA):** Deep dive into patient data to uncover patterns and correlations using Pandas and Data Visualization libraries.
- **Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling features for optimal model performance.
- **Predictive Modeling:** Training and evaluating various Machine Learning algorithms to find the most accurate model for stroke prediction.
- **Interactive Web UI:** A user-friendly Streamlit application that utilizes the trained model to make on-the-fly predictions.

---

## 📂 Project Structure

```text
Stroke_Prediction_Analysis/
├── healthcare-dataset-stroke-data.csv     # Raw dataset
├── preprocessed_stroke_data.csv           # Cleaned and processed dataset
├── ML Models For Stroke Predictions.ipynb # Jupyter Notebook containing EDA & Modeling
├── ML_Model_For_Stroke_predection.pkl     # Serialized (trained) Machine Learning model
├── streamlit_app.py                       # Streamlit application script
└── README.md                              # Project documentation
