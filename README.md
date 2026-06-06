# Home_Loan_Default_Prediction_DL
An end-to-end Deep Learning project that predicts whether a customer is likely to default on a home loan using historical financial and demographic data. The project focuses on handling imbalanced datasets, feature preprocessing, neural network modeling, and business-oriented evaluation metrics for financial risk prediction.

# 🏦 Home Loan Default Prediction using Deep Learning

## 📌 Project Overview

- Loan default prediction is one of the most important challenges in the banking and financial sector. Financial institutions need reliable systems to identify high-risk customers before approving loans.

- This project uses Deep Learning techniques to predict whether a customer will default on a home loan based on historical customer and loan-related data. The primary focus of the project is handling imbalanced data and improving the detection of loan defaulters.

## 🎯 Business Problem

Loan defaults can lead to significant financial losses for banks and lending institutions. Predicting potential defaulters in advance helps organizations:

- Reduce financial risk
- Improve loan approval strategies
- Make data-driven lending decisions

## 📂 Dataset Information

Datasets Used: 
1. loan_data.csv
- Contains customer demographic, financial, and loan-related features
2. Data_Dictionary.csv
- Contains descriptions of all dataset features

## 📊 Dataset Details
- Records: 307,000+
- Features: 122 columns
- Problem Type: Binary Classification

## 🎯 Target Variable
- TARGET = 1 → Loan Default
- TARGET = 0 → Loan Repaid




## 🔍 Exploratory Data Analysis (EDA)

Performed detailed analysis to understand:
- Missing values distribution
- Target variable imbalance
- Customer financial patterns
- Loan repayment behavior

## 📊 Key Findings
- Dataset was highly imbalanced
- Only ~8% customers were defaulters
- Proper imbalance handling was necessary for effective prediction



## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Handling missing values
- One-Hot Encoding for categorical features
- Feature Scaling using StandardScaler
- Train-Test Split
- Class Weighting to address imbalanced data

## 🤖 Deep Learning Model

Built a Neural Network using TensorFlow & Keras with:

- Dense layers with ReLU activation
- Dropout layers to reduce overfitting
- Sigmoid activation for binary classification

## 🧠 Model Architecture
Input Layer
- Hidden Layer (128 neurons)
- Hidden Layer (64 neurons)
- Hidden Layer (32 neurons)
- Output Layer (1 neuron)




## 📈 Model Evaluation

The model was evaluated using:

- Confusion Matrix
- Classification Report
- Recall (Sensitivity)
- ROC-AUC Score

# 📌 Important Insight

- Instead of focusing only on accuracy, the project prioritized Recall, because correctly identifying defaulters is more important in financial risk management.

# 📊 Results
- High Recall achieved for identifying loan defaulters
- Threshold tuning improved sensitivity significantly
- Demonstrated trade-off between accuracy and recall




# 🛠️ Technologies & Libraries Used
Programming Language:- Python 🐍
Libraries:- Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow, Keras

# 📁 Project Structure
📦 Home-Loan-Default-Prediction
 ┣ 📜 HOME_LOAN_DEFAULT_PREDICTION.ipynb
 ┣ 📜 loan_data.csv
 ┣ 📜 Data_Dictionary.csv
 ┣ 📂 images
 ┗ 📜 README.md


🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/home-loan-default-prediction.git


# 📊 Visualizations Included
- Target Variable Distribution
- Missing Value Analysis
- Recall over Epochs
- ROC Curve

# 🔮 Future Improvements
- Hyperparameter Tuning
- SMOTE for imbalance handling
- Advanced Neural Network architectures
- Model deployment using Streamlit or Flask
- Real-time prediction API

# 🧠 Key Learnings
- Handling imbalanced datasets in Deep Learning
- Importance of Recall in financial prediction problems
- Neural Network model building using TensorFlow & Keras
- Business-oriented model evaluation

👨‍💻 Author

MD Mozammil Ansary

Machine Learning & Data Science Enthusiast
Interested in AI-driven financial analytics
⭐ Show Your Support

If you found this project useful, consider giving it a ⭐
