# Parameter Optimization of Support Vector Machines

Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However, primarily, it is used for Classification problems in Machine Learning.

Some of the most important parameters of SVM such as kernel, C, and gamma can be changed in order to achieve a higher accuracy. This is called as Hyperparameter Tuning.

We can perform this task using GridSearchCV for optimizing these parameters.

In this python file, I've used a Fitness Function to optimize the parameters.

## Dataset Description
  The dataset at https://archive.ics.uci.edu/ml/machine-learning-databases/nursery/nursery.data contains information about nursery school admission applications. Specifically, the dataset includes information about 8 attributes of each application, as well as the class label for each application.

### Attribute Information:

The attributes in the dataset are:

1->Parents: the parents' occupation (categorical variable with 5 possible values)
2->Has_nurs: the quality of the nursery school the child currently attends (categorical variable with 5 possible values)
3->Form: the nursery school application form (categorical variable with 4 possible values)
4->Children: the number of children the parents have (ordinal variable with 4 possible values)
5->Housing: the type of housing the family lives in (categorical variable with 3 possible values)
6->Finance: the financial status of the family (categorical variable with 3 possible values)
7->Social: the social status of the family (categorical variable with 3 possible values)
8->Health: the health status of the child (categorical variable with 3 possible values)
The class label for each application specifies whether the application was accepted or rejected, and there are 5 possible values for this label.

This dataset has 12960 instances and there are no missing values. It can be used for classification tasks in machine learning.
### Source
 UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/machine-learning-databases/nursery/nursery.data 
 
### Result
|![dataframe](https://user-images.githubusercontent.com/72308638/233195924-4b0f25f9-aa45-4778-b168-1dc85451a46b.png)



# Convergence Graph 

<img width="705" alt="Screenshot 2023-04-20 at 2 16 41 AM" src="https://user-images.githubusercontent.com/72308638/233196356-ff4f089d-8902-4975-b5b8-96866ce9f191.png">


