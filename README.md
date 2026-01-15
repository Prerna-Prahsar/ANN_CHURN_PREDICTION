# Customer Churn Prediction using Artificial Neural Network (ANN)

## 📌 Project Overview

This project focuses on predicting **customer churn** (whether a customer will stay with or leave a company) using an **Artificial Neural Network (ANN)**. The trained model learns patterns from historical customer data and predicts churn for new customers. The final model is deployed using **Streamlit**, providing an interactive web-based interface for real-time predictions.

The project is divided into **three major parts**:

1. Model Training
2. Model Prediction
3. Web App & Deployment using Streamlit

---

## 🧠 1. Model Training

* A churn dataset is used containing customer demographic and account-related features.
* Data preprocessing steps include:

  * Handling categorical variables
  * Feature scaling
  * Train-test split
* An **Artificial Neural Network (ANN)** is designed and trained using TensorFlow/Keras.
* The model is compiled with:

  * **Adam optimizer**
  * **Binary Crossentropy loss function**
  * **Accuracy** as evaluation metric
* Early Stopping is applied to prevent overfitting and retain the best model weights.

---

## 🔍 2. Model Prediction

* The trained ANN model is used to predict customer churn.
* The model outputs a probability:

  * `0` → Customer is likely to **stay**
  * `1` → Customer is likely to **leave (churn)**
* A threshold (usually 0.5) is applied to convert probabilities into final predictions.

---

## 🌐 3. Streamlit App & Deployment

* A **Streamlit web application** is built to:

  * Take customer input features from the user
  * Preprocess the input data
  * Load the trained ANN model
  * Display churn prediction results in real time
* This makes the model easy to use for non-technical users.
* The app can be deployed on platforms like:

  * Streamlit Cloud
  * Render
  * Localhost

---

## 🛠️ Tech Stack

### 🔹 Programming Language

* Python

### 🔹 Libraries & Frameworks

* TensorFlow / Keras (ANN model)
* NumPy
* Pandas
* Scikit-learn (preprocessing & evaluation)
* Matplotlib / Seaborn (EDA & visualization)
* Streamlit (web app & deployment)

### 🔹 Tools

* Jupyter Notebook / VS Code
* Git & GitHub

---

## 🚀 Future Improvements

* Improve model accuracy using hyperparameter tuning
* Add feature importance analysis
* Deploy the model with FastAPI + Docker
* Add user authentication to the Streamlit app

---

## 👩‍💻 Author

**Prerna Prashar**
AIML Student | AI & Machine Learning Enthusiast
Interested in Deep Learning, NLP, and AI-based web applications

Email : prernaprashar7170@gmail.com
LinkedIn : www.linkedin.com/in/prerna-parashar-15859728a
github : https://github.com/Prerna-Prahsar
Thanks for checking out this project!
---

## 📄 License

This project is for educational and learning purposes.
