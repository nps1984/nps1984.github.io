---
title: Predicting WAR, the baseball kind
excerpt: Data science project to predict player WAR
priority: 1
author: nps1984
categories:
  - works
tags:
  - sklearn
  - matplotlib
#date/lastmod are optional
date: 2021-01-13 14:44:22 -0500
lastmod: 2021-01-13 14:44:22 -0500
---

# Project 1 - Generate Product Reviews
[Git Repo](https://github.com/nps1984/mlb-war-pred/tree/master/mlb-war-pred)

## Summary
This project was an attempt to predict WAR (wins above replacement) for MLB players.

The notebook uses the pybaseball library to download MLB statistics. It then uses the
sklearn library to perform feature selection. And finally it goes through a pipeline
and grid search cross validation to find the best model parameters. I didn't love the 
output of the model identified from the GridSearchCV, so I manually generated several 
models to review output.

## Results
I was able to achieve reasonable predictions, but my accuracy wasn't very good.
 


