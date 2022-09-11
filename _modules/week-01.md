---
title: Stochastic Model-based Optimization
---
**Abstract**{: .label .label-purple }

We introduce a new interpretation of first-order methods from the perspective of model function. Using the framework of model-based optimization, the analysis of several existing algorithms can be unified succinctly. Specifically, we focus on the stochastic model-based optimization (SMOD), a class of nonsmooth nonconvex problems which are prevalent in machine learning. To make SMOD more practical, we make two important extensions: 1) we show that the popular momentum trick can be incorporated with SMOD. 2) when the model function satisfies certain good approximation property, even the nonsmooth problems can be linearly accelerated by minibatching. Furthermore, we also briefly cover the topic of distributed optimization and discuss the advantage of certain models in the asynchronous environment.

- Advisor: Qi Deng
- Organizer: Wenzhi Gao


**Outline & Reference**{: .label .label-purple }

- Davis, Damek, and Dmitriy Drusvyatskiy. ‘‘Stochastic model-based minimization of weakly convex functions." SIAM Journal on Optimization 29.1 (2019): 207-239.
- Asi, Hilal, and John C. Duchi. ‘‘The importance of better models in stochastic optimization." Proceedings of the National Academy of Sciences 116.46 (2019): 22924-22930.
- Deng, Qi, and Wenzhi Gao. ‘‘Minibatch and Momentum Model-based Methods for Stochastic Weakly Convex Optimization." Advances in Neural Information Processing Systems 34 (2021): 23115-23127.
- Mukkamala, Mahesh Chandra. Bregman proximal minimization algorithms, analysis and applications. Diss. Universität Tübingen, 2022.
- Xu, Yangyang, et al. ‘‘Distributed Stochastic Inertial-Accelerated Methods with Delayed Derivatives for Nonconvex Problems." SIAM Journal on Imaging Sciences 15.2 (2022): 550-590.

**Schedule**{: .label .label-purple }

Sep 28
: [Intro](#)
  : [Notes](#), [Slides](#)