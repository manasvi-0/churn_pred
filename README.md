# 🔮 Customer Churn Prediction App (Streamlit)

This project is a web-based application for predicting **customer churn** using a pre-trained **Logistic Regression** model. It helps businesses identify customers who are likely to leave and provides actionable tips for **churn prevention** and **customer retention**.

---

## 🚀 Features

- Interactive Streamlit interface
- Churn prediction based on customer inputs
- Categorical and numerical input handling
- Tips for reducing churn and improving customer loyalty
- Pre-trained Logistic Regression model
- Real-time inference with `.pkl` model file

---

## 📦 Tech Stack

- **Python**
- **pandas**, **numpy**
- **scikit-learn**
- **Streamlit**
- **Pickle** (for model persistence)

---

## 🧠 Model Info

- **Algorithm:** Logistic Regression
- **Input Features:** Gender, SeniorCitizen, Partner, Dependents, Tenure, PhoneService, MultipleLines, Contract, TotalCharges
- **Preprocessing:** Label Encoding & Standard Scaling

---

## 🖥️ App UI Elements

| Feature            | Input Type      | Options / Description                  |
|--------------------|------------------|------------------------------------------|
| Gender             | Dropdown         | Female / Male                            |
| SeniorCitizen      | Dropdown         | Yes / No                                 |
| Partner            | Dropdown         | Yes / No                                 |
| Dependents         | Dropdown         | Yes / No                                 |
| Tenure             | Text Input       | Numeric input (months of service)        |
| PhoneService       | Dropdown         | Yes / No                                 |
| MultipleLines      | Dropdown         | Yes / No / No phone service              |
| Contract           | Dropdown         | One year / Two year / Month-to-month     |
| TotalCharges       | Text Input       | Numeric input (total charges in USD)     |

---

## 🧪 How to Run the App

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/churn_prediction_app.git
   cd churn_prediction_app
