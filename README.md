# Diabetes Prediction Machine Learning

This project predicts diabetes risk using the Pima Indians Diabetes Dataset. It applies machine learning models (Random Forest, Gradient Boosting, etc.) with feature engineering and tuning to improve prediction accuracy and sensitivity.

## Dataset

- 768 female patients with 8 diagnostic features + diabetes label

- Source: Kaggle Diabetes Dataset

## Key Steps

- Data cleaning (replace invalid zeros)

- Feature engineering (BMI and age groups, interaction terms)

- Model training with cross-validation

- Hyperparameter tuning

- Threshold adjustment for better recall (sensitivity)

## Result 
- Best model: Tuned Random Forest

- Accuracy: ~76%

- Recall optimized to ~80% for clinical screening

- Important features: Glucose, BMI, Age, and interactions

## How to use 

1. Install dependencies:

```bash
 pip install numpy pandas scikit-learn matplotlib seaborn

```
2. Open the Jupyter notebook (diabetes_prediction.ipynb) with:

```bash
 pjupyter notebook

```

3. Run all cells sequentially to load data, train models, and evaluate.

4. Use the provided prediction function to test new patient data.
