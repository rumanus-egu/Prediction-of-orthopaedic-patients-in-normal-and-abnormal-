# Prediction of orthopaedic patients in normal and abnormal using K Neerest neighbour and naive bayes classifier 

- Introduction
- Naive Bayes is a classification algorithm which is based on Bayes theorem with strong and naïve independence assumptions. It simplifies learning by assuming that features are independent of given class.This paper surveys about naïve Bayes algorithm, which describes its concept, hidden naïve Bayes, text classification, traditional naïve Bayes and machine learning.
- Also represents augmented naïve Bayes by examples. And at the end some applications of naïve Bayes and its advantages and disadvantages has discussed for a better understanding of the algorithm.

- Biomechanical Features of Orthopedic Patients
- In this project we are provided with multiple instances of orthopedic parameters and we are also provided with their classification as Normal or Abnormal
- To get started , first download the csv file from this link

- We have to implement K Nearest Neighbour, the algorithm is used to classify points according to class of their K nearest neighbour point

- And also on the the same dataset Implement a Gaussian Naive Bayes based classifier
- Now that you have the dataset , let us get started !
1. Section I : Accessing the Data
- Make a pandas DataFrame from the CSV
- How many variables does the dataset contain?
- What is the data about?
- What are we trying to predict here?
2. Section II : Exploratory Data Analysis
- Perform some descriptive statistics and make a note of your findings
- Plot appropriate graphs to understand the relation between the variables.
- Point out any observations and comment on the strength of the relationships if any.
3. Section III : Prepare data for Training!
- Make a new column symptom_class with the abnormal rows as 1 and the normal rows as 0, drop the class column
- Split the entire dataset into independent features and symptoms as the response variable
- Normalize the variables.
4. Section IV : Training with KNN
- Use train_test_split from sklearn and split the parameters and classes into train and test sets
- Starting with three nearest neighbours , train your KNN model and make a note of accuracy and other diagnostics for both training and test sets.
- Try with increasing the k value and check if there is any improvement in model performance. Use different value to arrive at the optimal value of k.
- Evaluate your final model using appropriate metrics for classification and comment on them.
5. Section V : Training with Naive Bayes
- Now , fit a Naive Bayes Classifier to the same data.
- Train a NB model with default arguments and make a note of training and test metrics
- What are your inferences on the relative performance between the KNN and NB based models?
- Which of these models would you recommend and with what reasons ?
6. Section VI : Wraping it up ! (This is optional but good for... like spinach...)
- Which of these models performed better ?
- Test these two models on other datasets as well !
  -To get started you could try these on
    -The IRIS Dataset
    -The Breast Cancer Dataset
-What other datasets these two models would perform well in?
