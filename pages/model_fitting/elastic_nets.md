---
title: Elastic Networks
tags:
keywords: "topic" # new keywords requiere to create a new tag file
last_updated: "June 1, 2020"
summary: "Elastic networks offer a hybrid between LASSO and ridge regressions."
published: true
sidebar: model_fitting_sidebar #name of yml sidebar file withouth extension
permalink: elastic_nets.html
folder: model_fitting
---


{% include note.html content="Please utilize the template below as a reference for your contribution. Adapt the template when deemed necessary" %}

## What is Elastic Net Regression/Classification?

Elastic net regression/classification offer a hybrid between LASSO regression (or classification) and ridge regression (or classification). It uses two hyperparameters: lambda and alpha. Lambda is a shrinkage parameter; it affects how much coefficients are "shrunk" by the model to reduce the likelihood of overfitting the training data. Alpha is a mixing parameter; it affects how close the penalization process is to pure LASSO (alpha = 1) or pure ridge (alpha = 0). Alpha values between 0 and 1 indicate a blend of LASSO and ridge penalizations. 


## Recommended Path for Learning

* Video overview of the concepts behind ridge regression (L2 penalization). Part of a 3-video series on regularization. (https://www.youtube.com/watch?v=Q81RR3yKn30)
* Video overview of the concepts behind LASSO regression. Part 2 of a video series on regularization. (https://www.youtube.com/watch?v=NGf0voTMlcs)
* Video overview of the concepts behind elastic net regression. Part 3 of a series on regularization. (https://www.youtube.com/watch?v=1dKRdX9bfIo)

## Further Learning

## Video

* Video overview of how to implement elastic net, lasso, and ridge regression in R. Assumes knowledge of the concepts behind these three types of regression as taught in the 3-part Regularization series linked above in the Recommended Path for Learning. (https://www.youtube.com/watch?v=ctmNq7FgbvI&t=42s)
* Video 2

## Applied papers 

* Paper 1
* Paper 2

## Online tutorials

* Online tutorial 1
* Online tutorial 2

## Theory papers 
* Paper 1
* Paper 2

{% include links.html %}
