# 📊 Customer Churn Prediction App

This is a machine learning web application that predicts whether a customer is likely to churn using a trained Deep Learning model. The project leverages TensorFlow, Scikit-Learn, and Streamlit to provide an interactive and insightful churn analytics tool.

---

## ✨ Features
✅ Predicts customer churn probability in real time

🧠 Built using a trained Neural Network model

🔎 Handles feature encoding (Label + One-Hot Encoding)

📏 Applies feature scaling for accurate predictions

💻 User-friendly Streamlit interface

---

## 🛠️ Tech Stack

- Python

- TensorFlow / Keras

- Scikit-Learn

- Streamlit

- Pandas & NumPy

---

## 📂 Project Structure
├── app.py

├── model.h5

├── label_encoder_gender.pkl

├── onehot_encoder_geography.pkl

├── scaler.pkl

└── README.md

---

## ⚙️ Installation & Setup
#### 1️⃣ Clone the Repository
git clone <repository-link>
cd <project-folder>

#### 2️⃣ Install Dependencies
pip install -r requirements.txt

#### 3️⃣ Run the Application
streamlit run app.py

---

## 🚀 How It Works

#### 1️⃣ User inputs customer details such as:

- Geography

- Gender

- Credit Score

- Age

- Balance

- Number of Products

- Credit Card Status

- Active Membership

- Estimated Salary

#### 2️⃣ Data undergoes:

- Label Encoding

- One-Hot Encoding

- Standard Scaling

### 3️⃣ The Neural Network predicts the churn probability and displays:

🔴 Customer likely to churn, or

🟢 Customer not likely to churn

---

## 🎯 Use Cases

- Banking & Finance

- Telecom

- SaaS & Subscription Services

- Customer Retention Analytics

---

## 🔮 Future Enhancements

- Add SHAP/LIME for model explainability

- Deploy to Streamlit Cloud / AWS / Azure

- Add database support

- Improve UI/UX
  
---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.
