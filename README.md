# Prodigy_DS_03

🔍 Project: Customer Purchase Prediction using Decision Tree Classifier
This project builds a Decision Tree Classifier to predict whether a customer will purchase a product or service based on demographic and behavioral data. We use the Bank Marketing dataset from the UCI Machine Learning Repository.

📂 Dataset
Source: UCI Machine Learning Repository - Bank Marketing
Description: The dataset contains information on customers contacted for a marketing campaign by a bank.
Target Variable: y (binary: "yes" = purchase, "no" = no purchase)
Features:
Demographics: Age, Job, Marital Status, Education, etc.
Behavioral Data: Previous campaign outcomes, contact method, number of contacts, etc.

🛠 Tech Stack
Programming Language: Python 🐍
Libraries:
pandas (data manipulation)
numpy (numerical computing)
matplotlib & seaborn (visualization)
sklearn (Decision Tree, model evaluation)

🚀 Implementation Steps

1️⃣ Data Preprocessing
Load dataset (bank.csv)
Handle missing values
Convert categorical features using Label Encoding / One-Hot Encoding
Split dataset into training and testing sets

2️⃣ Train a Decision Tree Classifier
Fit a DecisionTreeClassifier from sklearn.tree
Tune hyperparameters (max_depth, criterion, min_samples_split)

3️⃣ Model Evaluation
Accuracy, Precision, Recall, F1-score
Confusion Matrix
Feature Importance

📊 Results & Observations
Achieved X% accuracy (to be evaluated after running the model).
Top Features influencing purchase decisions: Age, Previous Campaign Outcome, Contact Method, etc.

🏆 Future Enhancements
Optimize using GridSearchCV
Compare with Random Forest and Gradient Boosting
Deploy using Flask / Streamlit
