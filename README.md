# AI-ML-TASK-5
AI & ML Internship - Task 5: Decision Trees and Random Forests
Objective
To implement and evaluate tree-based machine learning models — Decision Tree and Random Forest — using the Heart Disease Dataset. This task focuses on:

Reducing overfitting in decision trees
Comparing with ensemble methods like Random Forest
Visualizing the decision-making process
Interpreting feature importance
Using cross-validation for robust evaluation
 Dataset
File Name: heart.csv
Records: 1025 patient records
Target Variable: target
1 → Heart Disease Present
0 → No Heart Disease
Tools & Technologies
Google Colab (Recommended)
Python
Libraries: pandas, matplotlib, seaborn, scikit-learn
✅ Features Implemented
1️⃣ Decision Tree Classifier
Trained with max_depth=4 to control overfitting
Visualized using plot_tree() for interpretability
Evaluated using accuracy and classification metrics
2️⃣ Random Forest Classifier
Trained with 100 decision trees (n_estimators=100)
Significantly higher performance than single decision tree
Feature importances extracted and visualized
3️⃣ Feature Importance Plot
Identifies key medical features like cp, thalach, oldpeak, and ca
4️⃣ Cross-Validation
Used 5-fold cross-validation to ensure robust model performance
📊 Results Summary
Model	Accuracy	Cross-Validation Accuracy
Decision Tree	80.00%	83.41%
Random Forest	98.54% ✅	99.71% ✅
✅ Random Forest outperformed Decision Tree in both accuracy and stability.

▶ How to Run in Google Colab
Open Google Colab
Create a new notebook
Upload heart.csv using the sidebar "Files" tab
Copy and paste the full code from the notebook or provided .py file
Run all cells one by one to see output and graphs
 Files Included
heart.csv — Dataset file
aiml-task5.ipynb — Main notebook (optional)
README.md — Project documentation
 Author
MOHAMMEDI UMMUL
AI & ML Internship – Task 5
