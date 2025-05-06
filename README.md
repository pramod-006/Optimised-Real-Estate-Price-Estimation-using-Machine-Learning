# 🏠 Optimised Real Estate Price Estimation using Machine Learning

This project is designed to estimate the price of real estate properties using Machine Learning techniques. The system takes user input (such as location, number of bedrooms, square footage, etc.) through a web interface and predicts the property price using a trained machine learning model on the backend. The model has been optimized for better accuracy and performance.

---

## 📂 Project Structure


---

## ✅ Features

- End-to-end ML pipeline from data preprocessing to deployment
- Optimized model for accurate real estate price prediction
- Interactive web interface for input collection
- Flask REST API for model inference
- Lightweight, modular and production-ready design

---

## 🧠 Machine Learning Model

The model was developed using:

- Data preprocessing (handling null values, encoding, scaling)
- Feature engineering and selection
- Training using algorithms like Linear Regression, Lasso Regression, and Decision Tree Regressor
- Evaluation metrics such as RMSE and R² score
- Final model serialization using `pickle`

---

## 🌐 Frontend (client/)

- `index.html`: User form for inputting location, area (sqft), BHK, and bathrooms
- `app.css`: Basic styling for the web UI
- `app.js`: JavaScript to collect inputs and send API requests to the backend

---

## 🔧 Backend (server/)

- `server.py`: Hosts Flask application, handles endpoints like `/predict_home_price`
- `util.py`: Loads trained model, handles preprocessing and prediction logic

---

## 🧪 Model & Dataset (model/)

- `model.ipynb`: Contains the full machine learning pipeline – from data analysis and visualization to model training
- `columns.json`: Stores all feature names required for inference and used during training

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Optimised-Real-Estate-Price-Estimation-using-Machine-Learning.git
cd Optimised-Real-Estate-Price-Estimation-using-Machine-Learning


Added initial README file
