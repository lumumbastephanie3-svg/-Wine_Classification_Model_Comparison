# -Wine_Classification_Model_Comparison
This project explores and compares the performance of multiple supervised machine learning classification algorithms using the Wine dataset from Scikit-learn. The objective was to evaluate how different classification models perform on the same dataset by comparing their predictive accuracy and other evaluation metrics. 

## Overview

The project follows a complete machine learning workflow, including exploratory data analysis (EDA), data preprocessing, model training, evaluation, and comparison of results to identify the best-performing algorithm.

---

## Objectives

- Perform exploratory data analysis on the Wine dataset.
- Prepare the dataset for machine learning.
- Train multiple classification algorithms.
- Evaluate model performance using standard classification metrics.
- Compare the strengths and weaknesses of different models.

---

## Dataset

The project uses the **Wine Dataset** available in the Scikit-learn library.

Dataset characteristics:

- 178 wine samples
- 13 numerical features
- 3 wine classes
- No missing values

---

## Machine Learning Models

The following classification algorithms were implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Support Vector Machine (SVM)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Kaggle

---

## Workflow

1. Load and explore the dataset.
2. Perform exploratory data analysis (EDA).
3. Standardize numerical features.
4. Split data into training and testing sets.
5. Train six classification models.
6. Evaluate each model using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix
7. Compare model performance.

---

## Results

| Model | Accuracy |
|--------|---------:|
| Random Forest | ~100% |
| Logistic Regression | ~98% |
| Support Vector Machine | ~98% |
| Decision Tree | ~96% |
| K-Nearest Neighbors | ~94% |
| Naive Bayes | ~90% |

Random Forest achieved the highest classification accuracy, followed closely by Logistic Regression and Support Vector Machine, demonstrating strong predictive performance on the Wine dataset.

---

## Key Learnings

Through this project, I gained practical experience in:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature scaling
- Supervised Machine Learning
- Classification model evaluation
- Model comparison
- Performance interpretation

---

## Future Improvements

- Perform hyperparameter tuning using GridSearchCV.
- Apply cross-validation for more reliable evaluation.
- Perform feature selection.
- Test ensemble boosting methods such as XGBoost and AdaBoost.
- Deploy the best-performing model as a web application.

---

## Repository Structure

```
wine-classification-models/

│── README.md
│── requirements.txt
│── classification_models.ipynb
│
├── data/
│     └── wine_dataset.csv
│
├── images/
│     ├── class_distribution.png
│     ├── correlation_heatmap.png
│     ├── confusion_matrix_rf.png
│     └── model_comparison.png
```

---

## Stephannie Awuor Lumumba

**Stephannie Awuor Lumumba**

Economics & Statistics Graduate | Data Analytics | Machine Learning | Artificial Intelligence
