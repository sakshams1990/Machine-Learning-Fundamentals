# Machine Learning

What is Machine Learning ?

**Machine Learning** can be defined as field of study that gives computers to learn without being explicitly programmed. In basic terms, Machine Learing is all about making predictions or classifications based on the business problem.

# Fundamentals of Machine Learning
## Cross Validation

Cross Validation method splits the dataset into train and test making sure each portion of the dataset can act as train and test. It is normally termed as N fold cross validation. For e.g. 10 Fold Cross validation means , the whole data set is distributed into 10 parts. In each of 10 iterations, 1 part acts as test dataset and 9 parts act as train dataset. The result is summarised for all the iterations and are shown.

Apart from train-test split, cross validation is also used in tuning parameters when training a machine learning model.

## Confusion Matrix

![alt text](https://miro.medium.com/max/712/1*Z54JgbS4DUwWSknhDCvNTQ.png)

**Confusion Matrix** is a performance measurement for classification based Machine Learning problems. The table contains 4 different cobinations of Actual and Predicted.
It is extremely useful for measuring Recall, Precision, Specificity, Accuracy and most importantly AUC-ROC Curve.

Let us take an example with reference to  Heart Disease analogy.

**True Positive** 

Actual - The patient is suffering from heart disease.

Predicted - The patient is predicted to be suffering from heart disease.

**True Negative** 

Actual - The patient is not suffering from heart disease.

Predicted - The patient is predicted not to be suffering from heart disease.

**False Positive** 

Actual - The patient is not suffering from heart disease.

Predicted - The patient is predicted to be suffering from heart disease.

**False Negative** 

Actual - The patient is suffering from heart disease.

Predicted - The patient is predicted not to be suffering from heart disease.

**Sensitivity** or **Recall**

Sensitivity = TP/(TP+FN)

Out of all the positive classes, how much we predicted correctly. It should be high as possible.

**Specificity**

Specificity = TN/(TN+FP)

Out of all the negative classes, how much we predicted correctly.

**Precision**

Precision = TP/(TP+FP)

Out of all the positive classes we have predicted correctly, how many are actually positive.

**Accuracy**

Out of all the 4 combinations of actual and predicted, how many were predicted correctly. This is expected to be as high as possible.

**F-measure**

F-measure = (2 * Recall * Precision)/(Recall + Precision)

It is difficult to compare 2 models solely based on recall and precision. Hence , F-score becomes the measurable parameter for comparison. F-score helps to measure Recall & Precision at the same time using Harmonic Mean in place of Arithmetic Mean by punishing the extreme values.

## Bias and Variance





