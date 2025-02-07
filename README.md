# Health Insurance Fraud Detection using Machine Learning

## Overview
This project focuses on detecting fraudulent activities in the health insurance sector using machine learning techniques. The goal is to build a predictive model that can identify fraudulent claims more effectively than traditional rule-based systems. By analyzing historical data, the model uncovers patterns and characteristics associated with fraudulent claims, enabling proactive fraud detection.

### Key Objectives:
- **Assess Limitations of Traditional Fraud Detection:** Evaluate existing fraud detection methods and identify areas for improvement.
- **Identify Fraud Patterns:** Analyze historical data to uncover unique traits indicative of potential fraud.
- **Develop a Predictive Model:** Build a machine learning model to enhance fraud detection accuracy.
- **Compare Model Performance:** Evaluate the model's performance against traditional methods using metrics like accuracy, precision, and recall.

---

## Dataset
The dataset used in this project contains information about health insurance claims, including:

- **Demographic Data:** Age, Gender, Marital Status, Occupation, etc.
- **Financial Data:** Annual Income, Total Claim Amount, Amount Paid by Insurance, etc.
- **Behavioral Data:** Frequency of Claims, Previous Claims Amount, etc.
- **Fraud Indicators:** Whether the claimant has been involved in fraudulent activities or received suspicious offers.

📂 **Dataset Link:** [Click here to access the dataset](https://docs.google.com/spreadsheets/d/1UZievI9G_8P7WlHJA4q10udrATbLUYBV/edit?usp=sharing&ouid=101953658808213032825&rtpof=true&sd=true)

---

## Methodology

### 1. Data Preprocessing:
- Cleaned and standardized the dataset.
- Encoded categorical features using `LabelEncoder`.
- Created a target variable (`fraud_involvement`) to indicate fraudulent claims.

### 2. Handling Imbalanced Data:
- Applied **SMOTE (Synthetic Minority Oversampling Technique)** to balance the dataset.

### 3. Feature Scaling:
- Standardized features using `StandardScaler` to ensure consistent scaling.

### 4. Model Building:
- Trained a **Logistic Regression model** to classify claims as fraudulent or non-fraudulent.
- Evaluated the model using **accuracy, precision, recall, and F1-score**.

### 5. Cross-Validation:
- Performed **5-fold cross-validation** to ensure the model's robustness.

---

## Results 📊
The logistic regression model achieved the following results:

- **Accuracy:** 🎯 100%
- **Precision:** ✅ 100%
- **Recall:** 🔥 100%
- **F1-Score:** 📊 100%

### Cross-validation results:
- **Mean CV Accuracy:** 100%
- **Standard Deviation of CV Scores:** 0.0

These results indicate that the model performs exceptionally well in detecting fraudulent claims.

---

## Code Implementation 🖥️
The project is implemented in **Python** using the following libraries:

- `pandas` - For data manipulation and analysis.
- `scikit-learn` - For model building, evaluation, and preprocessing.
- `imbalanced-learn` - For handling imbalanced data using **SMOTE**.

### 🔑 Key Steps in the Code:
1. Load and preprocess the dataset.
2. Encode categorical features and create the target variable.
3. Apply **SMOTE** for oversampling.
4. Split the dataset into **training** and **testing** sets.
5. Train and evaluate the **logistic regression model**.
6. Perform **cross-validation** and output results.

---

## Future Work 🚀
- Experiment with **other machine learning algorithms** (e.g., **Random Forest, Gradient Boosting, Neural Networks**).
- Incorporate **additional features or external datasets** to improve model performance.
- Deploy the model as a **web application** for real-time fraud detection.

---

### 🏆 **Contributions & Feedback**
Feel free to **contribute** to this project by suggesting improvements or submitting pull requests!  
For any inquiries, you can **reach out via GitHub Issues**.

📌 **Star⭐ this repo** if you found it helpful!

---

