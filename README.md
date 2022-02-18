# Polynomial Regression

---

# Introduction

Radwait, a computer scientist, recently got a girlfriend and wants to buy a house to move in with her. He wants to buy the best possible house at the lowest possible cost. He goes to his friend Bajaj, a realtor, and asks him for data that can help him in his task. We need to help Radwait calculate the bias and variance of a trained model which can help him select the best possible house.

# Bias-Variance Tradeoff

When we discuss model prediction, it is important to understand the various prediction errors - bias and variance. There is a trade-off between a model’s ability to minimize bias and variance.
A proper understanding of these errors would help in distinguishing between a layman and an expert in Machine Learning. Before using different classifiers, it is important to understand how to select a classifier to use.

Let us get started and understand some basic definitions that are relevant. 

- **Bias** is the difference between the average prediction of our model and the correct value which we are trying to predict. A model with high bias does not generalise the data well and oversimplifies the model. It always leads to a high error on training and test data.
- **Variance** is the variability of a model prediction for a given data point. Again, imagine you can repeat the entire model building process multiple times. The variance is how much the predictions for a given point vary between different realisations of the model.
- **Noise** is any unwanted distortion in data. Noise is anything that is spuri- ous and extraneous to the original data, that is not intended to be present in the first place, but was introduced due to faulty capturing process.
- **Irreducible error** is the error that cannot be reduced by creating good models. It is a measure of the amount of noise in the data. Here, it is important to understand that no matter how good we make our model, our data will have certain amount of noise or irreducible error that cannot be removed.

If our model is too simple and has very few parameters then it may have high bias and low variance. On the other hand, if our model has a large number of parameters then it is going to have high variance and low bias. So we need to find the right (or good) balance without overfitting and underfitting the data.

# Linear Regression

Linear Regression is a supervised machine learning algorithm where the predicted output is continuous and has a constant slope. It’s used to predict values within a continuous range, (e.g. sales, price) rather than trying to classify them into categories (e.g. cat, dog). 

There are two main types:

- Simple Regression
- Multivariable Regression

Simple Regression deals with a single dependent and independent variable whereas, Multivariable Regression deals with a single dependent variable depending on multiple independent variable.

# Polynomial Regression

Linear Regression can only produce an output with a constant slope i.e a straight line. But what if our model requires it to have polynomial shape.

To do so we manipulate multivariable regression. Instead of n independent variable, we use n dependent variables which are powers of one independent variable from 1 to n. 

The weights that we get for each power will be its co-efficient, using which we can model a polynomial.


# Code

**code.ipynb** was the code written initially. It is a bulkier version as it contains many for loops. But it may provide clarity to the reader about what is happenning and my thought process while attempting the tasks.

**updated_code.ipynb** is the finalized version. It gives the same result as *code.ipynb* but is the vectorized form of it. It provides the user insight on how to write a sleek and sexy code.