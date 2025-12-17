💳 Credit Card Fraud Detection using Machine Learning
📌 Project Overview

Credit card fraud is a major challenge in the financial sector due to the highly imbalanced nature of transaction data. This project aims to detect fraudulent credit card transactions using machine learning techniques while handling class imbalance effectively.

The solution follows a complete end-to-end data science workflow, including data preprocessing, exploratory data analysis (EDA), feature scaling, imbalance handling, model training, and evaluation.

🎯 Objective

To build and evaluate multiple machine learning models that can accurately classify transactions as:

Fraudulent (1)

Non-Fraudulent (0)

Special emphasis is placed on F1-score, as it provides a better measure for imbalanced datasets than accuracy.

📂 Dataset

The dataset contains anonymized transaction features to preserve privacy.

Each transaction is labeled as fraud or non-fraud.

The dataset is highly imbalanced, with fraudulent transactions representing a very small fraction of the total data.


🛠️ Project Workflow
1. Data Collection & Exploration

Loaded and inspected the dataset

Checked shape, column names, data types

Verified missing values and duplicates

Performed statistical summary using describe()

2. Data Preprocessing

Dropped unnecessary columns

Checked and handled null values

Scaled features using StandardScaler

Addressed class imbalance using:

SMOTE (Synthetic Minority Over-sampling Technique)

Class weights (class_weight='balanced')

3. Exploratory Data Analysis (EDA)

Fraud vs Non-Fraud distribution (countplot)

Feature correlation analysis (heatmap)

Visualized model performance using bar plots

Identified patterns and relationships in the data

4. Feature Engineering

Prepared features for modeling

Ensured proper scaling for distance-based models

5. Model Selection & Training

The following models were trained and evaluated:

Logistic Regression

Support Vector Machine (SVM)

Random Forest Classifier

Gradient Boosting Classifier

Each model was trained using the same train-test split for fair comparison.

6. Model Evaluation

Models were evaluated using:

Accuracy Score

F1 Score

Classification Report

Confusion Matrix

📌 F1-score was prioritized due to severe class imbalance.

📊 Results

SMOTE significantly improved fraud detection performance

Ensemble and margin-based models performed better than simple linear models

The final comparison was visualized using a bar graph for easy interpretation

🧠 Key Insights

Accuracy alone is misleading for imbalanced datasets

SMOTE + class weighting improves minority class detection

F1-score is the most reliable metric for fraud detection

Proper feature scaling improves model stability

🚀 Future Enhancements

Implement cross-validation for better generalization

Perform hyperparameter tuning using GridSearchCV

Add anomaly detection techniques (Isolation Forest, Autoencoders)

Deploy the model as a real-time fraud detection API

Build an interactive dashboard using Power BI or Tableau

🧰 Tech Stack

Programming Language: Python

Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn

📁 Repository Structure
├── data/
│   └── credit_card_data.csv
├── notebooks/
│   └── Credit_Card_Fraud_Detection_EDA.ipynb
├── README.md

🧑‍💻 Author

Amaan Uddin
Aspiring Data Analyst / Data Scientist

📬 Feel free to connect and share feedback!

⭐ If you like this project

Don’t forget to star ⭐ the repository and share it!
