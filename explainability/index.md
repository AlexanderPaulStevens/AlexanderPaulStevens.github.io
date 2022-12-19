---
title: Explainability
layout: page
show-avatar: True
---
# Research Project around Explainability in Process Outcome Prediction

---
layout: post
title: Explainability in Process Outcome Prediction
subtitle: Alexander Stevens, Johannes De Smedt
thumbnail-img: /assets/img/guidelines.png
tags: [conference, explainability]
comments: true
---

Predicting the outcome of various sorts of processes has seen a strong uptake in recent years
due to the advances in machine and deep learning. Although a recent shift has been made in
the field of process outcome prediction to use models from the explainable artificial intelligence
field, the evaluation still occurs mainly through predictive performance-based metrics, thus not
accounting for the explainability, actionability, and implications of the results of the models. This
paper addresses explainability through the properties interpretability and faithfulness in the field
of process outcome prediction. We introduce metrics to analyse these properties along the main
dimensions of (business) process data: the event, case, and control flow attributes. This allows
comparing inherently created explanations with post-hoc explanations techniques, for which we
benchmark seven classifiers on thirteen real-life events logs covering a range of transparent and
non-transparent machine learning and deep learning models complemented with post-hoc (modelagnostic
or model-dependent) explainability techniques. Next, this paper contributes a set of
guidelines named X-MOP which allows selecting the appropriate model by providing insight into
how the varying preprocessing, model complexity, and explainability techniques typical in process
outcome prediction influence the explainability of the model.

![guidelines](https://user-images.githubusercontent.com/75080516/207954132-4742ce74-7031-4595-a488-a97d98f0a428.png)

---
# Interpretable Machine Learning
A must read book written by Christoph Molnar
![IML](https://user-images.githubusercontent.com/75080516/207945781-bdedc6d6-3c67-4c10-8f58-17e88c36d447.png)

Machine learning has great potential for improving products, processes and research. But computers usually do not explain their predictions which is a barrier to the adoption of machine learning. This book is about making machine learning models and their decisions interpretable.

After exploring the concepts of interpretability, you will learn about simple, interpretable models such as decision trees, decision rules and linear regression. The focus of the book is on model-agnostic methods for interpreting black box models such as feature importance and accumulated local effects, and explaining individual predictions with Shapley values and LIME. In addition, the book presents methods specific to deep neural networks.

All interpretation methods are explained in depth and discussed critically. How do they work under the hood? What are their strengths and weaknesses? How can their outputs be interpreted? This book will enable you to select and correctly apply the interpretation method that is most suitable for your machine learning project. Reading the book is recommended for machine learning practitioners, data scientists, statisticians, and anyone else interested in making machine learning models interpretable.

The book is accessible with this [link](https://christophm.github.io/interpretable-ml-book/).

{: .box-warning}
**Warning:** I did not contribute to this book, nor did I specifically asks for permission to post this. 
