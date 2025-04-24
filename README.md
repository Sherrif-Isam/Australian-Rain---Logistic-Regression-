🌧️ Australian Rain Prediction using Logistic Regression


This project tackles a real-world classification problem: predicting whether it will rain tomorrow in Australia based on weather conditions recorded today. It demonstrates the complete machine learning pipeline from data cleaning to model evaluation and persistence using scikit-learn.


📊 Dataset

Source: Kaggle – Rain in Australia Dataset

Size: ~142,000 rows, 24 columns

Target: RainTomorrow (Yes/No)



📚 What This Project Covers

Downloading and loading a real-world dataset

Exploratory data analysis and visualization

Handling missing values in both numeric and categorical columns

Feature scaling to a (0, 1) range using StandardScaler

One-hot encoding of categorical variables

Creating training, validation, and test sets

Training a Logistic Regression model with scikit-learn

Evaluating the model using validation/test accuracy

Saving and loading the model using joblib



🧠 Key Learnings

Understanding how to preprocess real-world data for classification

Using pipelines for consistent training and evaluation

The impact of feature engineering on logistic regression

Importance of splitting validation and test sets for trustworthy evaluation

How to persist models for deployment or future use



🛠️ Tools & Libraries

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Joblib

Google Colab



🚀 How to Run

Clone the repository: git clone https://github.com/Sherrif-Isam/Australian-Rain---Logistic-Regression-.git

Open the notebook in Google Colab or Jupyter: australian_rain_prediction.ipynb

Run each cell step-by-step to explore data processing, modeling, and evaluation.



✅ Status

Project complete

Model trained and saved

Validated using both validation and test datasets

📌 Author
Sherrif Isam
GitHub: @Sherrif-Isam
