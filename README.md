# Loan-Approval-Prediction
Built a predictive model for loan approval decisions using machine learning techniques

## Project Overview
The Loan Approval Prediction project utilizes machine learning models to predict whether a loan should be approved for an applicant. The dataset includes features such as applicant information and financial details, which are used to determine the likelihood of loan approval.

## Data Description
The dataset consists of various features that describe the applicants and their financial status:
- **Gender:** Male/Female
- **Married:** Yes/No
- **Dependents:** Number of dependents
- **Education:** Graduate/Not Graduate
- **Self_Employed:** Yes/No
- **ApplicantIncome:** Income of the applicant
- **CoapplicantIncome:** Income of the co-applicant
- **LoanAmount:** Loan amount applied for
- **Loan_Amount_Term:** Term of the loan in months
- **Credit_History:** Credit history of the applicant
- **Property_Area:** Urban/Semiurban/Rural

## Data Preprocessing
Data preprocessing involves cleaning the data, handling missing values, encoding categorical variables, and normalizing numerical features. This step is crucial for improving the performance of the machine learning models.

## Model Building
Several machine learning models were used in this project:
1. **Random Forest**
2. **Logistic Regression**
3. **Support Vector Classifier (SVC)**
4. **Decision Tree**
5. **K-Nearest Neighbors (KNN)**

## Evaluation
The models were evaluated using various metrics such as precision, recall, F1-score, and accuracy. The performance of each model for the test set is summarized below:

| Model               | Precision | Recall | F1-Score | Accuracy |
|---------------------|-----------|--------|----------|----------|
| Random Forest       | 0.85      | 0.92   | 0.88     | 0.825    |
| Logistic Regression | 0.81      | 0.94   | 0.87     | 0.80     |
| SVC                 | 0.69      | 0.99   | 0.82     | 0.691    |
| Decision Tree       | 0.78      | 0.77   | 0.77     | 0.688    |
| KNN                 | 0.71      | 0.80   | 0.75     | 0.638    |

The Random Forest model emerged as the best-performing model with the highest F1-score and accuracy.

## Conclusion
The Random Forest model was the most effective in predicting loan approvals, balancing precision, recall, F1-score, and accuracy. This model can help financial institutions make informed decisions by evaluating the risk associated with each loan application.

## Future Work
Future enhancements may include:
- Using more sophisticated feature engineering techniques.
- Exploring different model architectures and hyperparameter tuning.
- Incorporating more real-world data to improve the model's robustness.
