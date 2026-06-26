# 🏏 Cricket Score Prediction using Deep Learning

A Deep Learning project that predicts the **final innings score** of a cricket team based on the current match situation. By analyzing historical cricket match data and live match parameters, the model estimates the expected total score using a neural network regression model.

---

## 📌 Project Overview

Cricket score prediction is a regression problem where the objective is to estimate the final score of a batting team during an ongoing innings. This project leverages Deep Learning techniques to learn scoring patterns from historical match data and generate accurate score predictions.

The model considers various match attributes such as batting team, bowling team, current score, wickets fallen, overs completed, and recent scoring rate to estimate the final innings total.

---

## 🚀 Features

- Predicts the final innings score of a cricket team
- Deep Learning-based regression model
- Data preprocessing and feature engineering
- Exploratory Data Analysis (EDA)
- Model training and performance evaluation
- Accurate score estimation using live match statistics
- Simple and scalable prediction pipeline

---

## 📂 Dataset

The model is trained on historical cricket match data containing features such as:

- Batting Team
- Bowling Team
- Venue
- Current Runs
- Wickets Lost
- Overs Completed
- Runs Scored in Last 5 Overs
- Wickets Lost in Last 5 Overs
- Final Innings Score (Target Variable)

The dataset is cleaned, encoded, and preprocessed before training the Deep Learning model.

---

## 🛠️ Tech Stack

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## 📊 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Train-Test Split
7. Build Deep Learning Model
8. Model Training
9. Performance Evaluation
10. Score Prediction

---

## 🧠 Model Architecture

The Deep Learning model consists of:

- Input Layer
- Multiple Dense Hidden Layers
- ReLU Activation Functions
- Dropout Layers to reduce overfitting
- Output Layer for regression

### Training Configuration

- **Optimizer:** Adam
- **Loss Function:** Mean Squared Error (MSE)
- **Evaluation Metrics:** MAE, MSE, RMSE

---

## 📈 Evaluation Metrics

The model performance is evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help measure prediction accuracy and evaluate the model's ability to generalize on unseen data.



---


## 💡 Future Enhancements

- Include player-level performance statistics
- Incorporate pitch and weather conditions
- Add venue-specific historical analysis
- Real-time score prediction using live cricket APIs
- Hyperparameter optimization
- Deploy the model using Streamlit or Flask
- Improve model interpretability using SHAP

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Deep Learning
- Artificial Neural Networks
- Regression Modeling
- Feature Engineering
- Data Preprocessing
- Model Evaluation
- Sports Analytics
- Predictive Modeling
- TensorFlow & Keras

---

## 👨‍💻 Author

**Utsav Mathuria**

Chemical Engineering Undergraduate  
National Institute of Technology Warangal

**GitHub:** https://github.com/utsav133

---

## ⭐ Support

If you found this project useful, consider giving the repository a **⭐ Star** to support the project.
