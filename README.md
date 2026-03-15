# ❤️ Heart Disease Prediction App

This project is a **Streamlit web application** that predicts the risk of heart disease based on user‑provided medical parameters.  
It uses a trained **K‑Nearest Neighbors (KNN) model**, along with preprocessing tools (scaler and column mappings), to deliver real‑time predictions.

---

## 📂 Project Structure
HEART/
│
├── app.py                # Main Streamlit application
├── knn.pkl               # Trained KNN model
├── scaler.pkl            # Fitted scaler for preprocessing
├── columns.pkl           # Expected feature columns
└── README.md             # Project documentation
└── requirements.txt            # Required 


---

## 🚀 Features
- Interactive UI built with **Streamlit**.
- Input fields for medical attributes (age, cholesterol, blood pressure, etc.).
- Automatic preprocessing using a saved **scaler**.
- Prediction using a trained **KNN model**.
- Clear output messages with emoji indicators:
  - ✅ Low Risk of Heart Disease
  - ⚠️ High Risk of Heart Disease

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/Ayushi028/Heart.git
   cd Heart
