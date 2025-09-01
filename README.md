# Heart-disease-logistic-regression
# Predicting Heart Disease using Logistic Regression   

# Dataset Description: Cleveland Heart Disease Dataset  

This project uses the [Cleveland Heart Disease dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease) from the UCI Machine Learning Repository.  
It contains **303 patient records** with **14 attributes** (clinical, demographic, and diagnostic variables).  
The goal is to predict the presence of heart disease (*target* variable).  

---

## Variables  

- **age**: Age of the individual (years).  
- **sex**: Gender (1 = male, 0 = female).  
- **cp (chest pain type)**:  
  - 0 = Typical angina (all criteria present)  
  - 1 = Atypical angina (two of three criteria satisfied)  
  - 2 = Non-anginal pain (less than one criterion satisfied)  
  - 3 = Asymptomatic (no criteria satisfied)  

- **trestbps**: Resting blood pressure on admission (mmHg).  
- **chol**: Serum cholesterol level (mg/dL).  
- **fbs**: Fasting blood sugar > 120 mg/dL (1 = true, 0 = false).  
- **restecg (resting ECG results)**:  
  - 0 = Normal  
  - 1 = ST-T wave abnormality (T-wave inversions and/or ST elevation/depression > 0.05 mV)  
  - 2 = Probable/definite left ventricular hypertrophy (Estes' criteria)  

- **thalach**: Maximum heart rate achieved.  
- **exang**: Exercise-induced angina (1 = yes, 0 = no).  
- **oldpeak**: ST depression induced by exercise relative to rest (in mm).  
- **slope**: Slope of the peak exercise ST segment:  
  - 0 = Upsloping  
  - 1 = Flat  
  - 2 = Downsloping  

- **ca**: Number of major vessels (0–3) colored by fluoroscopy.  
- **thal (thalassemia)**:  
  - 1 = Normal  
  - 2 = Fixed defect  
  - 3 = Reversible defect  

- **target**: Presence of heart disease (1 = disease, 0 = no disease).  

---

## Notes  
- This dataset is widely used in medical ML studies for benchmarking.  
- Missing values have been handled in the original UCI dataset.  
- For more details, see the [UCI repository page](https://archive.ics.uci.edu/ml/datasets/heart+disease).  


This project investigates the predictive power of logistic regression on the Cleveland Heart Disease dataset.  
It combines exploratory data analysis (EDA) with model training and evaluation, reporting an accuracy of ~76% and sensitivity of 82%.  

## Key Highlights
- Performed data cleaning, pre-processing, and visualisation.  
- Conducted exploratory analysis of demographic and clinical variables.  
- Trained and evaluated a logistic regression model (scikit-learn).  
- Reported precision, recall, F1-score, and confusion matrix.  
- Discussed clinical implications, limitations, and future directions.  

## Tools & Libraries
- Python (NumPy, pandas, scikit-learn, matplotlib, seaborn)  
- Jupyter Notebook  

## Results
- Accuracy: 75.8%  
- Sensitivity (Recall): 82%  
- Specificity: 68%  
