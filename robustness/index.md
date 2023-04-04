---
title: Robustness
layout: page
show-avatar: True
---
# Assessing the Robustness in Predictive Process Monitoring through Adversarial Attacks

As machine and deep learning models are increasingly leveraged in predictive process monitoring, the focus has shifted towards making these models explainable. 
The successful adoption of a model is dependent on whether decision-makers can trust the predictions and explanations made. 
However, recent studies have shown that deep learning models are vulnerable to adversarial attacks -small perturbations to the inputs- which trick deep learning algorithms into making incorrect predictions. 
An additional crucial property is that the explanations are robust against these adversarial attacks when the model decision was not affected. 
Therefore, this paper introduces a robustness assessment framework by investigating the impact of adversarial attacks on the robustness of predictive accuracy and explanations used in the field of predictive process monitoring. 
First, adversarial examples of cases in the independent test set are generated to examine the robustness of the predictive model against intentionally manipulated data. 
Next, the predictive models are compared with similar models trained on data imputed with adversarial attacks. We monitor the impact on predictive performance in terms of AUC at different stages of the case execution. 
Finally, the robustness of the explanations is calculated as the distance between the original explanations and the explanations extracted from the model trained on attacked data. We test multiple machine and deep learning techniques, namely the transparent logistic regression, random forests with Shapley values, and LSTM neural networks with attention. 
Results show that especially neural networks suffer from adversarial attacks, and the former two are mostly robust in terms of both predictive accuracy and explanations.

*Alexander Stevens, Johannes De Smedt, Jari Peeperkorn, Jochen De Weerdt*

![framework_robustness](https://user-images.githubusercontent.com/75080516/207954025-bd0ed25a-d0bd-403e-9eb0-63cf5ab1d94c.png)

Link to paper: <a href="https://ieeexplore.ieee.org/document/9980753)"> here </a>

# Manifold Learning to Improve Robustness and Generalization in Process Outcome Prediction

In recent years, machine and deep learning methods have been successfully introduced to the field of predictive process monitoring to perform several predictive tasks such as predicting the next activity, remaining time, or the future state of a process instance (case). Nonetheless, recent developments have shown the vulnerability of these models against adversarial attacks, tricking the algorithms into making incorrect predictions. Despite this, these incorrect predictions can help make a model generalize better, as it enables it to learn noise or specifically engineered (hidden) attacks. In this paper, we propose the use of manifold learning to generate natural adversarial examples that are restricted within the range of data that the model is trained on, i.e. adversarial examples that are restricted to its class-specific manifold. The experimental evaluation suggests that learning from these on-manifold adversarial examples disentangles the trade-off between adversarial robustness and generalization, showing that there exist models that remain accurate on new, unseen data, while being robust against worst-case adversarial treats. In some cases, the introduced methodology acts as an event log enhancement technique, as it even improves generalization. This paper paves the way for more accurate and robust predictive models in the field of predictive process monitoring.

*Alexander Stevens, Jari Peeperkorn, Johannes De Smedt, Jochen De Weerdt*

![On-manifold training](https://user-images.githubusercontent.com/75080516/229744467-9b6bad21-5f83-45a5-b40a-bbe4942faa33.PNG)
