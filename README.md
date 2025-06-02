 Task 5: Decision Trees and Random Forests  
Dataset: Heart Disease Dataset  
Objective: Build, evaluate, and compare decision tree and random forest classifiers.

---

 Overview  
In this project, we implement and evaluate two tree-based models — a Decision Tree and a Random Forest — to classify heart disease presence. We visualize the decision tree, evaluate overfitting, analyze feature importance, and apply cross-validation.

---

 Dataset Details  
- Source: [Kaggle - Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)  
- Target Variable: `target`  
  - 1 = Heart disease present  
  - 0 = No heart disease  
- Features: Age, sex, cholesterol, fasting blood sugar, max heart rate, etc.

---

 Tools Used  
- Python  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn

---

 Steps Performed  
1. Loaded and explored the dataset  
2. Preprocessed the data (train/test split, standardization)  
3. Trained a Decision Tree Classifier with max depth  
4. Visualized the tree using `plot_tree`  
5. Trained a Random Forest Classifier  
6. Compared accuracy and classification reports  
7. Analyzed feature importance  
8. Evaluated both models using cross-validation

---

 Evaluation Metrics  
- Accuracy: Measured on test set  
- Classification Report: Includes precision, recall, F1-score  
- Cross-validation: 5-fold evaluation for better generalization  
- Feature Importance: Ranked using Random Forest's built-in attribute

---

 Conclusion  
Both models performed well in classifying heart disease. Random Forest outperformed the Decision Tree slightly and provided better generalization with cross-validation. Tree visualization and feature importance added valuable interpretability to the model behavior.

---
