# InsuriFy - Medical Insurance Premium Classification

InsuriFy is a machine learning-based system designed to classify whether a medical insurance premium is high, based on demographic and personal information. The project explores multiple ML models and preprocessing techniques to develop a robust classification system that can assist insurance companies in evaluating client risk profiles and pricing strategies.

## 🔍 Project Objective

To predict whether an individual's insurance premium is **high** using features such as:
- Age
- Body Mass Index (BMI)
- Smoking status
- Region
- Number of children
- Gender

## 🧠 Machine Learning Models Used

- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

## ⚙️ Workflow Pipeline

1. **Data Cleaning**  
2. **Feature Engineering**
3. **Normalization** (L1, L2, MinMax, Standard)
4. **Model Training**
5. **Cross-Validation**
6. **Evaluation** (Accuracy, Precision, Recall, F1 Score)
7. **Hyperparameter Tuning**

## 📊 Exploratory Data Analysis (EDA)

Performed detailed EDA to visualize and understand how:
- Age
- BMI
- Smoking habits
- Region

affect the insurance charges. This step guided feature selection and model tuning.

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Cross-Validation (k-fold)

## 🚀 Key Findings

- **Random Forest** and **XGBoost** outperformed other models in terms of F1 Score and generalization.
- Normalization technique choice significantly impacted model performance, with **StandardScaler** giving the best results.
- Smoking status and BMI had the highest influence on premium classification.

## 🏁 Outcome

The system helps insurance providers:
- Evaluate client risk profiles more effectively
- Assign appropriate premium categories
- Automate risk-based premium recommendations

## 📁 Project Structure

