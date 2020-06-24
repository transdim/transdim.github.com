---
layout: page
title:  Learning Notes
cover:  false
menu:   true
order:  6
---

These learning notes cover the material that would advance the transdim project. The authors would like to learn more new knowledge to update the research.

Time Series Analysis
----------------------

- **Time sieres forecasting**

  - Deep Demand Forecast Models (GitHub repository: [https://github.com/jingw2/demand_forecast](https://github.com/jingw2/demand_forecast)): Pytorch Implementation of DeepAR, MQ-RNN, Deep Factor Models, LSTNet, and TPA-LSTM.
  
  - A paper [Temporal tensor transformation network for multivariate time series prediction](https://arxiv.org/pdf/2001.01051.pdf) (2020) combined tensor structure and transfomer for time series forecasting.
  
  - Paper [Joint forecasting and interpolation of graph signals using deep learning](https://arxiv.org/pdf/2006.01536.pdf) (2020): RNNs + graph signal processing.

Machine Learning
----------------------

- **Low-Rank Matrix/Tensor Completion**
  
  - Paper [Large-scale low-rank matrix learning with nonconvex regularizers](https://arxiv.org/pdf/1708.00146.pdf) (PAMI 2018): fast and nonconvex low-rank matrix completion models.
  
  - Paper [Efficient nonconvex regularized tensor completion with structure-aware proximal iterations](http://proceedings.mlr.press/v97/yao19a/yao19a.pdf) (ICML 2019): sparse plus low-rank structure + proximal iteration solution.
  
  - Paper [Scalable tensor completion with nonconvex regularization](https://arxiv.org/pdf/1807.08725v1.pdf) (2018): scalable tensor learning framework.



Optimization Methods
----------------------

- **Majorization Minimization algorithm**
  
  - Kenneth Lange (2018). [Examples of MM Algorithms (slide)](https://hua-zhou.github.io/teaching/biostatm280-2018spring/slides/20-mm/deLeeuw.pdf).
  
  - David R. Hunter, Kenneth Lange (2004). [A Tutorial on MM Algorithms](http://www.leg.ufpr.br/~paulojus/EM/Tutorial%20on%20MM.pdf).
  
  - A paper [Exact minimum rank approximation via Schatten p-norm minimization](https://www.sciencedirect.com/science/article/pii/S0377042714001010) applied the Majorization Minimization algorithm to solve the Schatten p-norm minimization problem.
