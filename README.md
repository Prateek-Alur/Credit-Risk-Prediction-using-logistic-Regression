
# Credit Risk Prediction Using Logistic Regression  

## Overview  
This Machine-Learning example uses a variety of credit-related risk factors to predict a potential client's credit risk.
This project predicts credit risk (loan approval status) using logistic regression. The dataset includes applicant demographics, financial details, credit history, and loan-related parameters. The model predicts whether a loan will be approved (`Loan_Status`) based on the input features. The project involves performance evaluation using metrics like FPR (False Positive Rate), TPR (True Positive Rate), accuracy, and the AUROC curve.  

## Dataset Description  
The dataset contains 981 records with the following columns:  

- **Gender**: Gender of the applicant (1: Male, 0: Female).  
- **Married**: Marital status of the applicant (1: Married, 0: Single).  
- **Dependents**: Number of dependents.  
- **Education**: Education level (1: Graduate, 0: Not Graduate).  
- **Self_Employed**: Employment status (1: Self-employed, 0: Not self-employed).  
- **ApplicantIncome**: Monthly income of the applicant.  
- **CoapplicantIncome**: Monthly income of the co-applicant.  
- **LoanAmount**: Amount of the loan requested.  
- **Loan_Amount_Term**: Loan term in months.  
- **Credit_History**: Credit history score (1: Good, 0: Bad).  
- **Property_Area**: Type of property area (1: Urban, 2: Semiurban, 3: Rural).  
- **Loan_Status**: Loan approval status (1: Approved, 0: Not Approved) - Target variable.  

## Project Highlights  
1. **Data Preprocessing**:  
   - Handling missing values.  
   - Encoding categorical variables.  

2. **Model Development**:  
   - Logistic regression was used as the classification algorithm.  
   - The dataset was split into training and testing sets for evaluation.  

3. **Evaluation Metrics**:  
   - **Accuracy**: Measures the overall correctness of the model.  
   - **FPR (False Positive Rate)**: Proportion of negative instances incorrectly classified as positive.  
   - **TPR (True Positive Rate)**: Proportion of positive instances correctly identified.  
   - **AUROC Curve**: Area Under the Receiver Operating Characteristic curve to measure classification performance.
   - 
## Visualizations  
- **Confusion Matrix**: Provides insights into true/false positives and negatives.  
- **ROC Curve**: Showcases the tradeoff between sensitivity and specificity.  

## Conclusion  
This project demonstrates the application of logistic regression to credit risk prediction, with a focus on evaluating model performance using robust metrics.

