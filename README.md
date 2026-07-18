# 🏦 Customer Churn Prediction using Artificial Neural Networks

A deep learning-based customer churn prediction system that estimates whether a bank customer is likely to leave the bank. The application uses an Artificial Neural Network (ANN) trained on customer data and provides predictions through an interactive Streamlit web application.

---

## 🚀 Features

- Predict customer churn probability
- Artificial Neural Network (TensorFlow/Keras)
- Interactive Streamlit interface
- Data preprocessing with encoding and feature scaling
- Real-time prediction based on user input
- Easy-to-use web application

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

---

## 📂 Project Structure

```
ANN-Classification-Churn/
│
├── app.py                     # Streamlit application
├── prediction.ipynb           # Prediction notebook
├── experiments.ipynb          # Model training experiments
├── model.h5                   # Trained ANN model
├── scaler.pkl                 # Feature scaler
├── label_encoder_gender.pkl   # Gender encoder
├── onehot_encoder_geo.pkl     # Geography encoder
├── Churn_Modelling.csv        # Dataset
├── requirements.txt
├── LICENSE
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/your-username/ANN-Classification-Churn.git
cd ANN-Classification-Churn
```

### Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

**Linux / macOS**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

Start the Streamlit application

```bash
streamlit run app.py
```

The application will open in your browser at

```
http://localhost:8501
```

---

## 📊 Input Features

The prediction model uses the following customer attributes:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Has Credit Card
- Active Member Status
- Estimated Salary

---

## 🤖 Model Overview

The model is built using an Artificial Neural Network (ANN) for binary classification.

### Data Preprocessing

- Label Encoding
- One-Hot Encoding
- Standard Feature Scaling

### Model

- TensorFlow / Keras Sequential Model
- Binary Classification
- Sigmoid Output Layer

---

## 📈 Prediction Output

The application returns:

- Customer churn probability
- Whether the customer is likely to churn or not

Example

```
Churn Probability: 0.82

Prediction:
Customer is likely to churn.
```

---

## 📦 Requirements

Install all required packages using

```bash
pip install -r requirements.txt
```

---

## 🎯 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Explainable AI using SHAP
- Model performance dashboard
- REST API using Flask or FastAPI
- Docker deployment
- Cloud deployment on AWS or Azure

---

## 👨‍💻 Author

**Shreyas T S**

If you found this project helpful, consider giving it a ⭐ on GitHub.
