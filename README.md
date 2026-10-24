
# Breast Cancer Classification Using Machine Learning

## Project Overview

This project applies supervised machine learning techniques to breast cancer classification using Python and Scikit-learn. It compares K-Nearest Neighbors (KNN) and Logistic Regression models to evaluate their ability to distinguish between malignant and benign breast cancer cases.

The project demonstrates practical skills in data preparation, model training, performance evaluation, cross-validation, and comparative analysis.

## Objectives

- Build and evaluate machine learning classification models.
- Compare KNN and Logistic Regression performance.
- Assess models using multiple evaluation metrics.
- Understand the importance of recall and false negatives in high-stakes classification.

## Technologies Used

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Methodology

1. **Data preparation:** Prepared the dataset and divided it into training and testing sets.
2. **Model training:** Trained KNN and Logistic Regression classifiers.
3. **Model evaluation:** Compared accuracy, precision, recall, F1-score, and confusion matrices.
4. **Cross-validation:** Assessed model performance across multiple validation folds.
5. **Model comparison:** Reviewed performance metrics to understand the strengths and limitations of each model.

## Results

Logistic Regression achieved the following results in my evaluation:

| Metric | Result |
|---|---:|
| Test accuracy | 98.25% |
| Mean cross-validation accuracy | 97.80% |

The models were also assessed using precision, recall, F1-score, and confusion matrices. These metrics provide a broader view of classification performance than accuracy alone.

## Key Learnings

- How to train and evaluate supervised machine learning models using Scikit-learn.
- How to compare classification algorithms using multiple performance metrics.
- Why cross-validation is useful for assessing model performance.
- Why recall and false-negative rates deserve particular attention in medical classification problems.

## Repository Contents

- `breast-cancer.ipynb` — Jupyter Notebook containing the project workflow, model training, evaluation, and results.

## Future Improvements

- Apply feature scaling and systematic hyperparameter tuning where appropriate.
- Compare additional classification algorithms.
- Analyze precision-recall trade-offs and ROC-AUC.
- Improve reproducibility by documenting dataset sources, preprocessing steps, and random seeds.

## Author

**GitHub:** [KE2541](https://github.com/KE2541)

## Disclaimer

This project is for educational and portfolio purposes only. It is not a clinically validated system and must not be used to diagnose breast cancer or guide medical decisions.
