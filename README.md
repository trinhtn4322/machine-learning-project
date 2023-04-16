# Classification & Prediction of Diabetes

- Diabetes is a chronic condition that affects millions of people worldwide. It occurs when the body is unable to properly regulate blood sugar levels, leading to high levels of glucose in the bloodstream
- Diabetes is a complex and multifaceted disease that can be challenging to diagnose and manage. However, with recent advances in artificial intelligence (AI) technology, healthcare professionals are now able to use AI-based tools to improve the accuracy of diabetes diagnosis and classification.
- Furthermore, AI can also assist with disease management by providing personalized treatment recommendations based on a patient's individual health data. 

# Dataset
- Link from kaggle: https://www.kaggle.com/competitions/diabetes-classification/data
+ I use 2 dataset : train.csv and test.csv
- Columns Description:

--- Feature: 
- Pregnancies: number of pregnancies of a woman.
- Glucose: a person's blood sugar, measured in mg/dL.
- BloodPressure: a person's systolic blood pressure, measured in units of mm Hg.
- SkinThickness: the thickness of the skin on the inside of the arm, measured in millimeters.
- Insulin: the amount of produced by a person's body, measured in units of µU/mL.
- BMI (Body Mass Index): a person's body mass index, calculated as weight (kg) divided by the square of height (m2).
- DiabetesPedigreeFunction: an indicator of how much diabetes runs in a person's family.
- Age: the age of a person.

--- TARGET VARIABLE
- Outcome: is the target variable in the diabetes prediction problem. It indicates whether a person has diabetes (Outcome = 1 if yes, Outcome = 0 otherwise)

![image](https://user-images.githubusercontent.com/115331941/232313957-79941751-341b-49e3-802b-a8c73fe221f7.png)


# Compare 3 machine learning algorithms: KNN, SVM, RF and Choose the best algorithm for this project

1. KNN: (K-Nearest Neighbors) is an algorithm based on finding k nearest neighbors
2. SVM: (Support Vector Machine) is a classification algorithm based on a best hyperplane to divide data into distinct classes.
3. RF:Random Forest is an ensemble-based method of decision trees.

# In project
Use Python and its libraries
- Pandas
- Sklearn
- Matplotlib
- Seaborn
- Imblearn

There are 8 parts in this Project
- Part 1: Clean data
- Part 2: Data processing and visualization
- Part 3: Split data
- Part 4: KNN
- Part 5: SVM
- Part 6: Random Forest 
- Part 7: Comparison of 3 algorithms
- Part 8: Prediction 
