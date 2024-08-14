---
title: "Counterfactual and Synthetic Control Method: Causal Inference with Instrumented Principal Component Analysis"
collection: research
permalink: /research/csc_ipca
date: 2024-08-01
venue: 'Working Paper'
excerpt: 'The fundamental problem of causal inference lies in the absence of counterfactual. In recent advances, researchers modelling the entire data generating process (DGP) to impute the missing counterfactual explicitly. This paper expands the interactive fixed effect (IFE) model by instrumenting covariates into factor loadings adding additional robustness.'
#paperurl: ''
#citation: ''
---
The fundamental problem of causal inference lies in the absence of counterfactual. Traditional methodologies impute the missing counterfactual implicitly or explicitly based on untestable or too stringent assumptions. Synthetic control methods (SCM) utilizes weighted average of control units to impute the missing counterfactual for the treated. Eventhough SCM relaxes some strict assumptions, it still requires the treated unit to be inside the convex hull formulated by controls avoiding extrapolation. In recent advances, researchers modelling the entire data generating process (DGP) to impute the missing counterfactual explicitly. This paper expands the interactive fixed effect (IFE) model by instrumenting covariates into factor loadings adding additional robustness. This methodology offers multiple benefits: firstly, it incorporates the strengths of previous SCM approaches, such as the relaxation of the untestable parallel trends assumption (PTA). Secondly, it does not require the targeted outcomes inside the convex hull formulated by controls. Thirdly, it eliminates the need for correct model specification required by IFE model. Finally, it inherits the ability of principal component anlaysis (PCA) to effectively handle high dimensional data and enhances the value extracted from numerous covariates.\\

[Download paper here](url:/files/congwang_cv.pdf)

[Replication](https://github.com/CongWang141/JMP/tree/main)