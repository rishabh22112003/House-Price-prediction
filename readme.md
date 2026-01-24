# House Price Prediction App 🏠

A **machine learning–based House Price Prediction application** built using **Python, scikit-learn, and Streamlit**.  
The app allows users to input house features and predicts the **estimated house price in real time** using a trained regression model.

---

## 🔍 Project Overview
This project predicts house prices based on important features such as **lot area, overall quality, year built, and basement size**.  
A pre-trained machine learning model is loaded using **Joblib** and deployed locally through a **Streamlit web interface** for easy interaction.

---

## ✨ Key Features
- Real-time **house price prediction**
- Simple and intuitive **Streamlit UI**
- Uses a **pre-trained regression model**
- Feature alignment using saved feature list (`all_feat.pkl`)
- Clean and fast inference

---

## 🧠 Model Details
- Algorithm: **Regression Model (scikit-learn)**
- Model File: `house_model.pkl`
- Feature Mapping File: `all_feat.pkl`
- Input Handling: Dynamic feature alignment to avoid missing columns

---

## 🖥️ Streamlit Application (Local UI)
The Streamlit interface allows users to:
1. Enter house details such as:
   - Lot Area
   - Overall Quality
   - Year Built
   - Total Basement Area
2. Click the **Predict Price** button
3. Instantly view the **predicted house price**

---

## 🚀 How to Run the Project Locally

# Install required dependencies
type in terminal of streamlit code  --->  streamlit run app1.py


## Dataset use
Ames Housing Dataset from kaggle
https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset