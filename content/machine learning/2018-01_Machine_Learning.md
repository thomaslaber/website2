---
title: "Machine Learning Overview"
date: 2018-01-03
categories:
  - "post"
  - "machine learning"
tags: 
  - "R"
  - "python"
  - "regression"
  - "machine learning"
thumbnail: "img/banner/rstudio.png"
draft: false
---


Broadly, there are three types of Machine Learning Algorithms..

## 1. Supervised Learning

How it works: This algorithm consist of a target or outcome variable (or dependent variable) which is to be predicted from a given set of predictors (independent variables). Using these set of variables, we generate a function that map inputs to desired outputs. The training process continues until the model achieves a desired level of accuracy on the training data. Examples of Supervised Learning: <a href="/machine-learning/linear-regression/">Regression</a>, <a href="/post/decision-threes/">Decision Tree</a>, <a href="/post/random-forest/">Random Forest</a>, <a href="/post/kNN/">KNN</a>, <a href="/post/logistic-regression/">Logistic Regression</a> etc.

## 2. Unsupervised Learning

How it works: In this algorithm, we do not have any target or outcome variable to predict / estimate.  It is used for clustering population in different groups, which is widely used for segmenting customers in different groups for specific intervention. Examples of Unsupervised Learning: Apriori algorithm, K-means.

## 3. Reinforcement Learning:

How it works:  Using this algorithm, the machine is trained to make specific decisions. It works this way: the machine is exposed to an environment where it trains itself continually using trial and error. This machine learns from past experience and tries to capture the best possible knowledge to make accurate business decisions. Example of Reinforcement Learning: Markov Decision Process

<a href="https://www.analyticsvidhya.com/blog/2017/09/common-machine-learning-algorithms/" target="_blank">Source</a> 

## Measurement metrics

Some measures of model accuracy like mean absolute error (MAE), mean absolute percentage error (MAPE), symmetric mean absolute percentage error (SMAPE), mean squared error (MSE) and root mean squared error (RMSE).

Mean squared error:

$$MSE = \displaystyle\frac{1}{n}\sum_{t=1}^{n}res_t^2$$ 

Root mean squared error:

$$RMSE = \displaystyle\sqrt{\frac{1}{n}\sum_{t=1}^{n}res_t^2}$$

Mean absolute error:

$$MAE = \displaystyle\frac{1}{n}\sum_{t=1}^{n}|res_t|$$

Mean absolute percentage error:

$$MAPE = \displaystyle\frac{100\%}{n}\sum_{t=1}^{n}\left |\frac{res_t}{y_t}\right|$$

