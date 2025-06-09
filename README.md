# 🏥 Medical Appointment No-Show Prediction

This project analyzes a real-world dataset of medical appointments in Brazil to predict whether patients will show up for their scheduled appointments.


## 📌 Project Goals

- Understand the key factors that influence appointment no-shows.
- Perform data cleaning and feature engineering.
- Handle class imbalance using SMOTE.
- Build and optimize a **Random Forest Classifier** using **RandomizedSearchCV**.
- Evaluate the model using classification metrics.



## 📂 Dataset

- Source: [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/joniarroba/noshowappointments)
- Rows: ~110,000
- Target: `No-show` (Yes or No)



## 🔧 Technologies Used

- Python (Pandas, NumPy)
- Seaborn & Matplotlib (for data visualization)
- Scikit-learn (Random Forest, train/test split, evaluation)
- imbalanced-learn (SMOTE for oversampling)
- Google Colab



## 🧠 Key Features Engineered

- **AwaitingTime**: Days between scheduled and appointment dates
- Binary encoding for `Gender` and `No-show`
- One-hot encoding for `Neighbourhood`



## ⚖️ Class Imbalance Handling

- Used **SMOTE** to synthesize minority class examples
- Applied `class_weight='balanced'` in the Random Forest Classifier



## 🚀 Model Performance

Random Forest Classifier with hyperparameter tuning via **RandomizedSearchCV**.

> Replace this with your actual performance once finalized:

- Accuracy: `62%`
- Precision: `32%`
- Recall: `74%`
- F1-score: `44%`



## 📈 Next Steps

- Try alternate models like XGBoost or LightGBM
- Deploy as a web app for real-time predictions
- Incorporate additional data (weather, transport)



## 💼 This belongs to:

- 👤 Lesego Maponyane 
- 📧 www.linkedin.com/in/lesego-maponyane
- 🧠 Data Science Project

---
