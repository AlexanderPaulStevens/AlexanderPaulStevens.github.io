---
title: Robustness
layout: page
show-avatar: True
---

![robustness](https://user-images.githubusercontent.com/75080516/207947027-cd6d329e-04cf-4721-ba49-060b17372979.png)

## Adversarial Attacks

These are attacks designed to fool your machine learning model

## Adversarial Examples

The examples that are very similar to your data, but have a different prediction than the original instance.

(to be continued)

---
# Assessing the Robustness in Predictive Process Monitoring through Adversarial Attacks
*Alexander Stevens, Johannes De Smedt, Jari Peeperkorn, Jochen De Weerdt*

![framework_robustness](https://user-images.githubusercontent.com/75080516/207946995-349594d1-858c-420e-89a5-f43735492ec7.png)

As machine and deep learning models are increasingly leveraged in predictive process monitoring, the focus has shifted towards making these models explainable. 
The successful adoption of a model is dependent on whether decision-makers can trust the predictions and explanations made. 
However, recent studies have shown that deep learning models are vulnerable to adversarial attacks -small perturbations to the inputs- which trick deep learning algorithms into making incorrect predictions. 
An additional crucial property is that the explanations are robust against these adversarial attacks when the model decision was not affected. 
Therefore, this paper introduces a robustness assessment framework by investigating the impact of adversarial attacks on the robustness of predictive accuracy and explanations used in the field of predictive process monitoring. 
First, adversarial examples of cases in the independent test set are generated to examine the robustness of the predictive model against intentionally manipulated data. 
Next, the predictive models are compared with similar models trained on data imputed with adversarial attacks. We monitor the impact on predictive performance in terms of AUC at different stages of the case execution. 
Finally, the robustness of the explanations is calculated as the distance between the original explanations and the explanations extracted from the model trained on attacked data. We test multiple machine and deep learning techniques, namely the transparent logistic regression, random forests with Shapley values, and LSTM neural networks with attention. 
Results show that especially neural networks suffer from adversarial attacks, and the former two are mostly robust in terms of both predictive accuracy and explanations.

/assets/img/framework_robustness.png
