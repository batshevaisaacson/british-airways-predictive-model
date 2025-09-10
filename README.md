# British Airways Predictive Model

### Overview  
Completed the **British Airways Data Science Virtual Experience** on Forage.  
Built predictive models to forecast whether customers complete bookings and identified the key drivers behind booking behavior.  

### Objectives  
- Predict booking completion using customer data  
- Compare classification models: Random Forest vs. Logistic Regression  
- Identify important features influencing customer booking decisions  

### Tools & Skills  
Python • Scikit-learn • Pandas • Machine Learning

### Methodology  
- **Data Preparation**: handled missing values, removed duplicates, encoded categorical variables, and explored class imbalance (15% completed vs. 85% not).  
- **Modeling**: trained Random Forest and Logistic Regression models.  
- **Evaluation**: compared models with accuracy, precision, recall, F1-score, and cross-validation.  
- **Interpretation**: analyzed feature importance and coefficients to extract business insights.  

### Results  
- **Random Forest**: high accuracy (~85%) but lower recall for completed bookings due to class imbalance.  
- **Logistic Regression**: improved recall (~71%) for booking completions with lower precision.  
- **Key Predictors**: purchase lead time, flight hour, length of stay, and customer origin/geograpjy were most influential.

### Files  
- [Python Script](BA_predictive_model.py)  
