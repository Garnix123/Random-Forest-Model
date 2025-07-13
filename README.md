# ✈️ Customer Satisfaction Prediction with Random Forest

## 📌 Overview
This project builds and tunes a **random forest classifier** to predict whether an airline customer will be satisfied with their flight experience.  
It uses a dataset of survey responses from **129,880 customers**, containing features like flight class, distance, and inflight entertainment ratings.

Random forests are powerful because they:
- Combine many decision trees
- Reduce variance and bias
- Lower the risk of overfitting

## ⚙️ Steps
- **Import libraries:** `numpy`, `pandas`, `sklearn` modules (`RandomForestClassifier`, `train_test_split`, `GridSearchCV`, and evaluation metrics), and `pickle` for saving the model
- **Exploratory Data Analysis (EDA):** Understand and clean the data
- **Data preparation:** Handle missing values, encode categories, etc.
- **Model building:** Train and tune the random forest model
- **Evaluation:** Use metrics like accuracy, precision, recall, and F1 score to measure performance

## 📊 Dataset (Obtained from Coursera's Google Advanced Data Analytics Certification)
Real-world customer survey data with features including:
- Class
- Flight distance
- Inflight entertainment score
- And more flight experience feedback

## ✅ Output
- Tuned random forest model
- Evaluation metrics and feature importance insights
- Pickled model file for future use

## 🤖 Author
Project for an airline to better understand and predict customer satisfaction.

---
Feel free to fork, modify, and explore!
