---
layout: post
title: Quantifying Explainability in Outcome-Oriented Predictive Process Monitoring
subtitle: Alexander Stevens, Johannes De Smedt, Jari Peeperkorn
thumbnail-img: /assets/img/definition.png
tags: [conference, explainability, XAI]
comments: true
---

The growing interest in applying machine and deep learning
algorithms in an Outcome-Oriented Predictive Process Monitoring
(OOPPM) context has recently fuelled a shift to use models from the explainable
artificial intelligence (XAI) paradigm, a field of study focused
on creating explainability techniques on top of AI models in order to
legitimize the predictions made. Nonetheless, most classification models
are evaluated primarily on a performance level, where XAI requires
striking a balance between either simple models (e.g. linear regression)
or models using complex inference structures (e.g. neural networks) with
post-processing to calculate feature importance. In this paper, a comprehensive
overview of predictive models with varying intrinsic complexity
are measured based on explainability with model-agnostic quantitative
evaluation metrics. To this end, explainability is designed as a symbiosis
between interpretability and faithfulness and thereby allowing to compare
inherently created explanations (e.g. decision tree rules) with posthoc
explainability techniques (e.g. Shapley values) on top of AI models.
Moreover, two improved versions of the logistic regression model capable
of capturing non-linear interactions and both inherently generating their
own explanations are proposed in the OOPPM context. These models
are benchmarked with two common state-of-the-art models with posthoc
explanation techniques in the explainability-performance space.

![definition](https://user-images.githubusercontent.com/75080516/207955809-7142abfd-b71a-4ffe-8889-c1078db73028.PNG)
