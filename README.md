# Milk Quality Prediction

The machine learning model developed aims to estimate the quality of milk using various
features extracted from the dataset. The dataset consists of a set of milk samples, with each
sample represented by several parameters: pH, temperature, taste, odor, fat content, turbidity, and
color. The target variable, or the label, is the grade of the milk, which is categorized as high,
medium, or low.


# Steps Followed
1)Data collection and processing
2)Data Visualization
3)Feature Selection
4)Model Selection

# Models Used 
1)Naive Bayes
2)Decision Tree

# Testing and Evaluation of a Model

In this ML model we have used a decision tree as this is a classification model and consists
of both numerical and categorical data. By using the non scaled features for training and testing
we have a built decision tree which has criterion as gini index and depth as 10. The accuracy of
the model is 0.97742. By using the scaled features for training and testing we have a built
decision tree which has criterion as gini index and depth as 10. The accuracy of the model is
0.97798. When we change the criterion to entropy and maximum depth is 9, we get the accuracy
as 0.98742. When we change the criterion to log loss and maximum depth is 9, we get the
accuracy as 0.98742. Therefore, we get the ideal value of maximum depth as 9.
By evaluating both the models of Naive Bayes and Decision tree, we have found out that
Decision tree is the best fit model for this dataframe.
