# Parameter Optimization of Support Vector Machines

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset Description
  The dataset at https://archive.ics.uci.edu/ml/machine-learning-databases/nursery/nursery.data contains information about nursery school admission applications. Specifically, the dataset includes information about 8 attributes of each application, as well as the class label for each application.

### Attribute Information:

The attributes in the dataset are:

Parents: the parents' occupation (categorical variable with 5 possible values)
Has_nurs: the quality of the nursery school the child currently attends (categorical variable with 5 possible values)
Form: the nursery school application form (categorical variable with 4 possible values)
Children: the number of children the parents have (ordinal variable with 4 possible values)
Housing: the type of housing the family lives in (categorical variable with 3 possible values)
Finance: the financial status of the family (categorical variable with 3 possible values)
Social: the social status of the family (categorical variable with 3 possible values)
Health: the health status of the child (categorical variable with 3 possible values)
The class label for each application specifies whether the application was accepted or rejected, and there are 5 possible values for this label.

This dataset has 12960 instances and there are no missing values. It can be used for classification tasks in machine learning.
### Source
 UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/machine-learning-databases/nursery/nursery.data 
 
### Result
| Sample  | Best Accuracy | Best Kernel | Best Nu | Best Epsilon |
| -----   | ------------- | ----------- | ------- | ------------ |
| 1 | 0.62 | Linear | 6.43 | 2.84 |
| 2 | 0.76 | Poly | 3.58 | 1.12 |
| 3 | 0.68 | Sigmoid | 9.96 | 1.14 |
| 4 | 0.69 | Sigmoid | 2.55 | 8.43 |
| 5 | 0.69 | Linear | 6.45 | 2.81 |
| 6 | 0.77 | Sigmoid | 3.39 | 2.81 |
| 7 | 0.62 | Linear | 8.88 | 2.77 |
| 8 | 0.72 | Linear | 5.11 | 5.34 |
| 9 | 0.27 | Poly | 0.81 | 4.44 |
| 10 | 0.77 | Poly | 8.53 | 0.52 |


# Convergence Graph 

![image](https://user-images.githubusercontent.com/73159662/233172351-999dcb03-af26-4069-bf5c-3a8ed16893ee.png)

