# Polynomial Regression

---

# Introduction

Radwait, a computer scientist, recently got a girlfriend and wants to buy a house to move in with her. He wants to buy the best possible house at the lowest possible cost. He goes to his friend Bajaj, a realtor, and asks him for data that can help him in his task. We need to help Radwait calculate the bias and variance of a trained model which can help him select the best possible house.

# Bias-Variance Tradeoff

When we discuss model prediction, it is important to understand the various prediction errors - bias and variance. There is a trade-off between a model’s ability to minimize bias and variance.
A proper understanding of these errors would help in distinguishing between a layman and an expert in Machine Learning. Before using different classifiers, it is important to understand how to select a classifier to use.

Let us get started and understand some basic definitions that are relevant. 

- Bias is the difference between the average prediction of our model and the correct value which we are trying to predict. A model with high bias does not generalise the data well and oversimplifies the model. It always leads to a high error on training and test data.
   <img src="https://latex.codecogs.com/svg.image?\bg_white&space;\text{Bias}&space;=&space;(\text{E}[\hat{f}(x)]&space;-&space;f(x))^2" title="\bg_white \text{Bias} = (\text{E}[\hat{f}(x)] - f(x))^2" />
    $$
    \text{Bias} = (\text{E}[\hat{f}(x)] - f(x))^2
    $$
    
    where $f(x)$ represents the true value, $\hat{f}(x)$ represents the predicted value


<img src="https://latex.codecogs.com/svg.image?\bg_black&space;\text{Bias}&space;=&space;(\text{E}[\hat{f}(x)]&space;-&space;f(x))^2" title="\bg_black \text{Bias} = (\text{E}[\hat{f}(x)] - f(x))^2" />
