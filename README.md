````md
# Customer Churn Prediction using ANN

## Overview
This project predicts whether a bank customer is likely to churn using an Artificial Neural Network (ANN) built with TensorFlow and Keras.  
A Streamlit web application is also developed to take user inputs and predict churn probability in real time.

---

## Features
- Customer churn prediction using ANN
- Data preprocessing and feature engineering
- Label Encoding and One-Hot Encoding
- Feature scaling using StandardScaler
- Hyperparameter tuning experiments
- Interactive Streamlit web app
- Real-time churn probability prediction

---

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Streamlit
- Matplotlib

---

## Dataset
The dataset used is the Bank Customer Churn dataset containing customer information such as:
- Credit Score
- Geography
- Gender
- Age
- Balance
- Number of Products
- Active Membership
- Estimated Salary

Target Variable:
- `Exited`
  - 1 → Customer Churned
  - 0 → Customer Retained

---

## Model Architecture
The model is built using an Artificial Neural Network (ANN) with:
- Input Layer
- Hidden Dense Layers
- ReLU Activation Function
- Output Layer with Sigmoid Activation

Loss Function:
- Binary Crossentropy

Optimizer:
- Adam Optimizer

---

## Project Structure


├── data/
│   └── Churn_Modelling.csv
│
└── notebooks/
    ├── experiments.ipynb
    ├── prediction.ipynb
    └── hyperparametertuningann.ipynb
Customer-Churn-Prediction/
│
├── app.py
├── requirements.txt
├── model.h5
├── scaler.pkl
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl


---

## Installation

Clone the repository:
```bash
git clone <your-github-repo-link>
````

Move into project directory:

```bash
cd Customer-Churn-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Streamlit App

```bash
streamlit run app.py
```

---

## How It Works

1. User enters customer details
2. Input data is encoded and scaled
3. ANN model predicts churn probability
4. Result is displayed on Streamlit interface

---

## Sample Prediction

The application displays:

* Churn Probability
* Whether the customer is likely to churn or not

---

## Future Improvements

* Improve model accuracy
* Deploy on cloud platforms
* Add more visualization dashboards
* Try advanced models like XGBoost

---

## Author

Girikant M Rai

```
```
