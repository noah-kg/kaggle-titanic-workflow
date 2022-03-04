![Kaggle Titanic Competition](https://cdn.activestate.com/wp-content/uploads/2021/05/kaggle-titanic-challenge.jpg)

# My Kaggle Workflow - Titanic Edition

The [legendary Kaggle competition](https://www.kaggle.com/c/titanic)! This competition is often touted as the best place for beginners to test their machine learning knowledge, and it serves as a fantastic stepping-off point for people who are interested in machine learning concepts. Both training and testing data sets [are provided](https://www.kaggle.com/c/titanic/data) by Kaggle.

In this project I demonstrate several things:
  * My ability to parse, clean, and analyze data
  * My ability to create a modular, reproducible workflow that can be used with any project
  * My ability to present both code and information in a digestible, easy-to-understand format
  * My willingness to learn and apply information about new models & algorithms

> The premise of the competition is simple: use machine learning to create a model that predicts which passengers survived the Titanic shipwreck. -[Kaggle description](https://www.kaggle.com/c/titanic/overview/description)

Since the premise of the project is to predict whether or not a passenger aboard the Titanic might survive, this project falls under the umbrella of **Binary Classifitcation**. In my attempt at this competition, I employed the use of several machine learning classifier models:
  * [Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression)
  * [K-Nearest Neighbors](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
  * [Random Forest](https://en.wikipedia.org/wiki/Random_forest)
  * [Support Vector Machine](https://en.wikipedia.org/wiki/Support-vector_machine)
  * [Stochastic Gradient Descent](https://en.wikipedia.org/wiki/Stochastic_gradient_descent)
  * [Linear Perceptron](https://en.wikipedia.org/wiki/Perceptron)

## My process for this project is as follows:
1. Process Data 
    - Identify and convert datatypes
    - Change and replace missing or zero values
    - Create one-hot encoding variables
    - Mapping categorical variables
2. Explore Data
    - Visualize distribution of variables
    - Identify any interesting relationships
3. Feature Engineering
    - Combine features to create new, useful features
4. Feature Selection
    - Identify which features can be most useful for our models
5. Model Selection & Tuning
    - Identify which machine learning model we should use
    - Tune hyperparameters for the models
6. Submision to Kaggle
    - Create submission file for Kaggle
    - Upload and compare to our predicted accuracy values

## Results
Through the use of [recursive feature elimination with cross-vlaidation (RFECV)](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFECV.html) and hyperparameter tuning with both [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html) and [RandomizedSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html) I was able to produce my most successful results with a Support Vector Machine. At the time of writing, I was able to achieve an accuracy of 78.7%, which I am very pleased with. This score put me in the **1535<sup>th</sup> position** out of **14,039**, one that I am also very proud of!

## Lessons Learned
This was one of the most fun projects I've worked on to date, and one that taught me a ton about data and machine learning. When I first attempted it, I had no experience whatsoever with Support Vector Machines, Stochastic Gradient Descent, or Linear Perceptron models. It took a lot of reading and testing to figure out how to properly implement them. Another challenge was understanding how RandomizedSearchCV worked. I spent a long time testing and tweaking the parameters to change when using it. This project helped me realize the importance of **structure** in a project, as it became very clear to me how quickly one can get lost in the code.
