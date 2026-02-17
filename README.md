# Task4_AI_ML_Internship

**Objective**

Build a binary classifier using Logistic Regression and evaluate its performance using standard classification metrics.


**Tools Used**

Python
Pandas
Matplotlib
Scikit-learn


**Dataset**

Breast Cancer Wisconsin dataset (from Scikit-learn)
569 samples
30 features
2 classes: Malignant (0) and Benign (1)

**Steps Performed**

1. Loaded dataset
     - Loaded dataset using sklearn.datasets.load_breast_cancer()
     - Converted features into Pandas DataFrame
2. Split into training (80%) and testing (20%)
   Split dataset into:
   80% Training Data
   20% Testing Data
   Used train_test_split() with random_state=42
3. Standardized features using StandardScaler
   Applied StandardScaler
   Standardized training and testing data separately
4. Trained Logistic Regression model
   Used LogisticRegression() from Scikit-learn
   Trained model on scaled training data
6. Evaluated using:
      - Confusion Matrix
    -  Precision
    Recall
    ROC-AUC Score
    ROC Curve
    Tuned classification threshold

   
**Sigmoid Function**

Logistic Regression uses:
σ(z)=1/1+e−z​
It converts output into probability (0–1) for classification.


**Conclusion**

Logistic Regression performed effectively for binary classification, with strong ROC-AUC and balanced precision-recall performance.
