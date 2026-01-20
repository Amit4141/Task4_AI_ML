Task 4: Feature Encoding & Scaling
Adult Income Dataset

Project Title:
Feature Engineering: Encoding & Scaling on Adult Income Dataset

Dataset:
Name: Adult Income Dataset  
Source: UCI Machine Learning Repository  
File Used: adult.csv  

Objective:
To preprocess the dataset using feature encoding and scaling techniques so that it becomes suitable for machine learning models.

Tools & Libraries Used:
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  

Tasks Performed:

1. Identify Feature Types  
Categorical features such as workclass, occupation, race, sex, etc.  
Numerical features such as age, fnlwgt, hours-per-week, etc.

2. Label Encoding  
Applied to:
- education  
- income  
Used where natural order exists.

3. One-Hot Encoding  
Applied to:
- workclass  
- marital-status  
- occupation  
- relationship  
- race  
- sex  
- native-country  
Used where no natural order exists.

4. Feature Scaling  
Applied StandardScaler  
Converted numerical features to:
- Mean = 0  
- Standard Deviation = 1  

5. Comparison Before & After Scaling  
Used statistical summaries and boxplots to compare feature distribution.

6. Impact of Scaling  
Scaling improves performance for:
- KNN  
- SVM  
- Logistic Regression  
- Neural Networks  

Scaling is less important for:
- Decision Trees  
- Random Forest  

7. Save Processed Dataset  
Final output saved as:
adult_preprocessed.csv

Project Files:
adult.csv – Raw dataset  
adult_preprocessed.csv – Encoded and scaled dataset  
Task4_Feature_Encoding_Scaling.ipynb – Jupyter Notebook  
README.md – Project documentation  

Final Outcome:
Understood feature encoding  
Learned scaling techniques  
Prepared ML-ready dataset  
Successfully completed Feature Engineering task  

