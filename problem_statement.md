Logistic Regression & Decision Trees on a Kaggle Dataset
Dataset Description
We will use the Pima Indians Diabetes Dataset (available on Kaggle: Diabetes Dataset).

Target Variable: Outcome

1 → Patient has diabetes

0 → Patient does not have diabetes

Features:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Tasks
Part A: Data Preprocessing
Load the dataset into a Pandas DataFrame.

Perform exploratory data analysis (EDA):

Show the first 5 rows.

Check for missing values.

Display basic statistics (mean, std, etc.).

Split the data into train (70%) and test (30%) sets.

Part B: Logistic Regression
Train a Logistic Regression model using the training data.

Predict on the test set.

Calculate and interpret the following metrics:

Accuracy

Precision, Recall, F1-score

Confusion Matrix

ROC Curve & AUC Score

Guiding Question:

Why is AUC-ROC a better evaluation metric than just accuracy in imbalanced datasets?
Part C: Decision Tree Classifier
Train a Decision Tree Classifier (use max_depth = 4).

Predict on the test set.

Calculate the same metrics as Logistic Regression.

Plot the Decision Tree and interpret the first split (which feature did it choose and why?).

Guiding Question:

Compare the Decision Tree’s interpretability vs. Logistic Regression’s coefficients.

Which one would you prefer in a medical diagnosis scenario? Why?

Part D: Comparison & Reflection
Compare Logistic Regression and Decision Tree results (accuracy, precision, recall, F1, AUC).

Discuss:

Which model performs better?

Which model is easier to interpret for doctors?

If the dataset is slightly imbalanced (more 0’s than 1’s), which metric (Precision or Recall) should be prioritized in diagnosing diabetes? Why?

