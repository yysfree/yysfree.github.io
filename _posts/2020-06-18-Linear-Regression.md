---
layout: post
mathjax: true
title: How to Employer Linear Regression from sklearn
---

linear regression modeling

$$y = \beta_0 + \beta_1 x1 +\beta_2 x2 + ... +\epsilon$$

first need to import sklearn and then call fit & predict method


```python
from sklearn.linear_model import LinearRegression
my_lr = LinearRegression()
my_lr.fit(X,y)
my_lr.predict(X,y)

```
