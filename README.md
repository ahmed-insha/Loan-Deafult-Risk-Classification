# Loan-Default-Risk-Classification
Leveraged data analysis and predictive modeling on loan application data to optimize credit risk assessment, enhance underwriting decisions, and present actionable insights via interactive dashboards.

## Project Overview  
This project focuses on analyzing borrower characteristics and financial history to identify key risk factors associated with loan defaults. Using **Exploratory Data Analysis (EDA)** and **predictive modeling**, we aim to provide insights that help financial institutions optimize their lending strategies and minimize risk.  

## Objective  
- Conduct EDA to uncover patterns and correlations related to loan defaults.  
- Build a predictive model to classify borrowers as likely to default or repay.  
- Use **Logistic Regression with PCA (Principal Component Analysis)** to reduce dimensionality and improve model performance.  

## Dataset  
The project uses three primary datasets:  
1. **application_data.csv** – Contains client details at the time of loan application.  
2. **previous_application.csv** – Contains historical loan application records.  
3. **columns_description.csv** – A data dictionary describing variable meanings.  

## Methodology  
1. **Data Preprocessing:**  
   - Cleaned and transformed the data.  
   - Handled missing values and outliers.  
   - Encoded categorical variables.  
2. **Exploratory Data Analysis (EDA):**  
   - Visualized key borrower attributes and their relationship with loan default.  
   - Identified trends in income, employment status, and previous credit history.  
3. **Feature Engineering:**  
   - Created new features from existing data to enhance model performance.  
4. **Dimensionality Reduction (PCA):**  
   - Applied PCA to retain **60% variance** while reducing the number of features.  
5. **Predictive Modeling:**  
   - Implemented **Logistic Regression** for classification.  
   - Evaluated model performance using **Accuracy, Precision, Recall, and F1-score**.  

## Model Performance  
- **Number of Principal Components Chosen:** 27  
- **Accuracy Score:** 68.51%  
- **Classification Report:**
             precision    recall  f1-score   support  

       0       0.68      0.73      0.70      3946  
       1       0.69      0.64      0.66      3714  

accuracy                           0.69      7660  


## Tools & Technologies Used  
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Visualization:** Power BI  


