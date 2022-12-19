---
title: Explainability
layout: page
show-avatar: True
---
# Explainability in Process Outcome Prediction: Guidelines to Obtain Interpretable and Faithful Models
*Alexander Stevens, Johannes De Smedt*
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

# Quantifying Explainability in Outcome-Oriented Predictive Process Monitoring
*Alexander Stevens, Johannes De Smedt, Jari Peeperkorn*

The growing interest in applying machine and deep learning algorithms in an Outcome-Oriented Predictive Process Monitoring (OOPPM) context has recently fuelled a shift to use models from the explainable artificial intelligence (XAI) paradigm, a field of study focused on creating explainability techniques on top of AI models in order to legitimize the predictions made. 
Nonetheless, most classification models are evaluated primarily on a performance level, where XAI requires striking a balance between either simple models (e.g. linear regression) or models using complex inference structures (e.g. neural networks) with post-processing to calculate feature importance. In this paper, a comprehensive overview of predictive models with varying intrinsic complexity are measured based on explainability with model-agnostic quantitative evaluation metrics. 
To this end, explainability is designed as a symbiosis between interpretability and faithfulness and thereby allowing to compare inherently created explanations (e.g. decision tree rules) with posthoc explainability techniques (e.g. Shapley values) on top of AI models.
Moreover, two improved versions of the logistic regression model capable of capturing non-linear interactions and both inherently generating their own explanations are proposed in the OOPPM context. 
These models are benchmarked with two common state-of-the-art models with posthoc explanation techniques in the explainability-performance space.

![definition](https://user-images.githubusercontent.com/75080516/207955809-7142abfd-b71a-4ffe-8889-c1078db73028.PNG)
