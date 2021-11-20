# Machine Learning Intro


## Bird's Eye View

First, we must clear up one of the biggest misconceptions about machine learning:

Machine learning is not about algorithms.

When you open a textbook or a university syllabus, you'll often be greeted by a grocery list of algorithms.

This has fueled the misconception that machine learning is about mastering dozens of algorithms. However, it's much more than that...

Machine learning is a comprehensive approach to solving problems...

...and individual algorithms are only one piece of the puzzle. The rest of the puzzle is how you apply them the right way.


Machine learning is the practice of teaching computers how to learn patterns from data, often for making decisions or predictions.

For true machine learning, the computer must be able to learn patterns that it's not explicitly programmed to identify.

### Key Terminology

Model - a set of patterns learned from data.

Algorithm - a specific ML process used to train a model.

Training data - the dataset from which the algorithm learns the model.

Test data - a new dataset for reliably evaluating model performance.

Features - Variables (columns) in the dataset used to train the model.

Target variable - A specific variable you're trying to predict.

Observations - Data points (rows) in the dataset.


### The 3 Elements of Great Machine Learning
1.  A skilled chef (human guidance)
2. Fresh ingredients (clean, relevant data)
3. Don't overcook it (avoid overfitting)

### The Blueprint
1
Exploratory Analysis

First, "get to know" the data. This step should be quick, efficient, and decisive.

2
Data Cleaning

Then, clean your data to avoid many common pitfalls. Better data beats fancier algorithms.

3
Feature Engineering

Next, help your algorithms "focus" on what's important by creating new features.

4
Algorithm Selection

Choose the best, most appropriate algorithms without wasting your time.

5
Model Training

Finally, train your models. This step is pretty formulaic once you've done the first 4.

## Exploratory Analysis

### Why explore your dataset upfront?

* You’ll gain valuable hints for Data Cleaning (which can make or break your models).

* You’ll think of ideas for Feature Engineering (which can take your models from good to great).

* You’ll get a "feel" for the dataset, which will help you communicate results and deliver greater impact.



### Start with Basics


First, you'll want to answer a set of basic questions about the dataset:

* How many observations do I have?
* How many features?
* What are the data types of my features? Are they * numeric? Categorical?
* Do I have a target variable?



### Plot Numerical Distributions

* Distributions that are unexpected
* Potential outliers that don't make sense
* Features that should be binary (i.e. "wannabe indicator variables")
* Boundaries that don't make sense
* Potential measurement errors


### Plot Categorical Distributions
Categorical features cannot be visualized through histograms. Instead, you can use bar plots.

In particular, you'll want to look out for sparse classes, which are classes that have a very small number of observations.


### Plot Segmentations

Segmentations are powerful ways to observe the relationship between categorical features and numeric features.


### Study Correlations


Finally, correlations allow you to look at the relationships between numeric features and other numeric features.

Correlation is a value between -1 and 1 that represents how closely two features move in unison. You don't need to remember the math to calculate them. Just know the following intuition:


## Data Cleaning

### Better Data > Fancier Algorithms



Data cleaning is one those things that everyone does but no one really talks about. Sure, it’s not the "sexiest" part of machine learning. And no, there aren’t hidden tricks and secrets to uncover.

However, proper data cleaning can make or break your project. Professional data scientists usually spend a very large portion of their time on this step.

Why? Because of a simple truth in machine learning:

Better data beats fancier algorithms.

In other words... garbage in gets you garbage out. Even if you forget everything else from this course, please remember this point.

In fact, if you have a properly cleaned dataset, even simple algorithms can learn impressive insights from the data!

Obviously, different types of data will require different types of cleaning. However, the systematic approach laid out in this lesson can always serve as a good starting point.

### Remove Unwanted observations

for example 

* Duplicate observations
* Irrelevant observations


### Fix Structural Errors

The next bucket under data cleaning involves fixing structural errors.

Structural errors are those that arise during measurement, data transfer, or other types of "poor housekeeping."

For instance, you can check for typos or inconsistent capitalization. This is mostly a concern for categorical features, and you can look at your bar plots to check.



### Filter Unwanted Outliers


### Handle Missing Data



## Feature Engineering


Feature engineering is about creating new input features from your existing ones.

In general, you can think of data cleaning as a process of subtraction and feature engineering as a process of addition.

This is often one of the most valuable tasks a data scientist can do to improve model performance, for 3 big reasons:

1. You can isolate and highlight key information, which helps your algorithms "focus" on what’s important.
2. You can bring in your own domain expertise.
3. Most importantly, once you understand the "vocabulary" of feature engineering, you can bring in other people’s domain expertise!

### Infuse Domain Knowledge


You can often engineer informative features by tapping into your (or others’) expertise about the domain.

Try to think of specific information you might want to isolate. Here, you have a lot of "creative freedom."

### Create Interaction Features


The first of these heuristics is checking to see if you can create any interaction features that make sense. These are combinations of two or more features.

By the way, in some contexts, "interaction terms" must be products between two variables. In our context, interaction features can be products, sums, or differences between two features.


### Combine Sparse Classes

Sparse classes (in categorical features) are those that have very few total observations. They can be problematic for certain machine learning algorithms, causing models to be overfit.

* There's no formal rule of how many each class needs.
* It also depends on the size of your dataset and the number of other features you have.
* As a rule of thumb, we recommend combining classes until each one has at least ~50 observations. As with any "rule" of thumb, use this as a guideline (not actually as a rule).


### Add Dummy Variables


Most machine learning algorithms cannot directly handle categorical features. Specifically, they cannot handle text values.

Therefore, we need to create dummy variables for our categorical features.

Dummy variables are a set of binary (0 or 1) variables that each represent a single class from a categorical feature.

The information you represent is exactly the same, but this numeric representation allows you to pass the technical requirements for algorithms.


### Remove Unused Features

Unused features are those that don’t make sense to pass into our machine learning algorithms. Examples include:

* ID columns
* Features that wouldn't be available at the time of prediction
* Other text descriptions

Redundant features would typically be those that have been replaced by other features that you’ve added during feature engineering.



## Algorithm Selection


### How to Pick ML Algorithms

n applied machine learning, individual algorithms should be swapped in and out depending on which performs best for the problem and the dataset. Therefore, we will focus on intuition and practical benefits over math and theory.



### Why Linear Regression is Flawed

Simple linear regression models fit a "straight line" (technically a hyperplane depending on the number of features, but it's the same idea). In practice, they rarely perform well. We actually recommend skipping them for most machine learning problems.

Their main advantage is that they are easy to interpret and understand. However, our goal is not to study the data and write a research report. Our goal is to build a model that can make accurate predictions.

In this regard, simple linear regression suffers from two major flaws:

1. It's prone to overfit with many input features.
2. It cannot easily express non-linear relationships.


### Regularization in Machine Learning


This is the first "advanced" tactic for improving model performance. It’s considered pretty "advanced" in many ML courses, but it’s really pretty easy to understand and implement.

The first flaw of linear models is that they are prone to be overfit with many input features.


###  Regularized Regression Algos

* Lasso Regression
* Ridge Regression
* Elastic-Net


### Decision Tree Algos

### Tree Ensembles



## Model Training

### How to Train ML Models

It might seem like it took us a while to get here, but professional data scientists actually spend the bulk of their time on the steps leading up to this one:

* Exploring the data.
* Cleaning the data.
* Engineering new features.


### Split Dataset


Think of your data as a limited resource.

* You can spend some of it to train your model (i.e. feed it to the algorithm).
* You can spend some of it to evaluate (test) your model.
But you can’t reuse the same data for both!
* If you evaluate your model on the same data you used to train it, your model could be very overfit and you wouldn’t even know! A model should be judged on its ability to predict new, unseen data.

Therefore, you should have separate training and test subsets of your dataset.

### What are Hyperparameters?

When we talk of tuning models, we specifically mean tuning hyperparameters.

There are two types of parameters in machine learning algorithms.

The key distinction is that model parameters can be learned directly from the training data while hyperparameters cannot.


### What is Cross-Validation?

Cross-validation is a method for getting a reliable estimate of model performance using only your training data.

There are several ways to cross-validate. The most common one, 10-fold cross-validation, breaks your training data into 10 equal parts (a.k.a. folds), essentially creating 10 miniature train/test splits.

These are the steps for 10-fold cross-validation:

1. Split your data into 10 equal parts, or "folds".
2. Train your model on 9 folds (e.g. the first 9 folds).
3. Evaluate it on the 1 remaining "hold-out" fold.
4. Perform steps (2) and (3) 10 times, each time holding out a different fold.
5. Average the performance across all 10 hold-out folds.
 
The average performance across the 10 hold-out folds is your final performance estimate, also called your cross-validated score. Because you created 10 mini train/test splits, this score is usually pretty reliable.


### Fit and Tune Models
```
    For each algorithm (i.e. regularized regression, random forest, etc.):
  For each set of hyperparameter values to try:
    Perform cross-validation using the training set.
    Calculate cross-validated score.
```

### Select Winning Model

By now, you'll have 1 "best" model for each algorithm that has been tuned through cross-validation. Most importantly, you've only used the training data so far.
