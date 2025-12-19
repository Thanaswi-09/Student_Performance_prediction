# Student_Performance_prediction

This project predicts student **pass/fail outcomes** using machine learning based on academic, social, and demographic factors.

## Tech Stack
- Python
- NumPy, Pandas
- Matplotlib
- Scikit-learn (SVM, Feature Selection)

## Model
- Linear Support Vector Machine (SVM)
- Chi-Square Feature Selection
- 5-Fold Cross Validation

## Scenarios Tested
1. Model with G1 & G2 exam scores  
2. Model with only G1 score  
3. Model without any exam scores  

## Evaluation
- Accuracy & Cross-validation
- Confusion Matrix
- False Pass & False Fail Rates
- Classification Report

## Dataset
- UCI Student Performance Dataset (`student-mat.csv`)
- Target: Final Grade (G3 → Pass/Fail)

## How to Run
```bash
pip install numpy pandas matplotlib scikit-learn
python main.py
