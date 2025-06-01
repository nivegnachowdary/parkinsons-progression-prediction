# 🧠 Parkinson’s Disease Progression Prediction

### Problem
Parkinson’s disease is a progressive neurological disorder. Early prediction of disease progression can help optimize treatment and intervention plans.

### Tools & Techniques
- Python, Pandas, Scikit-learn
- ML Models: SVM, Random Forest, Logistic Regression
- Feature Selection: RFE, SelectKBest
- Evaluation: Accuracy, ROC-AUC, k-Fold Cross Validation

###  Approach
- Preprocessed 5,875 voice recordings (jitter, amplitude, frequency)  
- Applied noise reduction and normalization  
- Used RFE and SelectKBest for feature selection  
- Trained multiple classification models and validated using cross-validation

### Results
- Achieved **15% improvement in model accuracy** over baseline  
- Enabled early-stage progression insights based on vocal biomarkers  
- Project aimed to support clinical decision-making for neurological care
