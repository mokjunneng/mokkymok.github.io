---
layout: post
title:  "Naive Bayes Classification"
date:   "2020-08-06"
categories: Speech & Language Processing
---

The goal of **classification** is to take a single observation, extract some useful features, and thereby classify the observation into one of a set of discrete classes.

There are two kinds of classifiers. **Generative** classifiers like Naive Bayes build a model of how a class could generate some input data. Given an observation, they return the class most likely to have generated the observation. **Discriminative** classifiers like logistic regression instead learn what features from the input are most useful to discriminate between the different possible classes.