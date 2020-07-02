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
  
  - Anish Agarwal, Abdullah Alomar, Devavrat Shah (2020). [On Multivariate Singular Spectrum Analysis](https://arxiv.org/pdf/2006.13448.pdf).


Machine Learning
----------------------

- **Low-rank matrix/tensor completion**
  
  - Paper [Large-scale low-rank matrix learning with nonconvex regularizers](https://arxiv.org/pdf/1708.00146.pdf) (PAMI 2018): fast and nonconvex low-rank matrix completion models.
  
  - Paper [Efficient nonconvex regularized tensor completion with structure-aware proximal iterations](http://proceedings.mlr.press/v97/yao19a/yao19a.pdf) (ICML 2019): sparse plus low-rank structure + proximal iteration solution.
  
  - Paper [Scalable tensor completion with nonconvex regularization](https://arxiv.org/pdf/1807.08725v1.pdf) (2018): scalable tensor learning framework.
  
  - Jing Ma, Qiuchen Zhang, Joyce C. Ho, and Li Xion (2020). [Spatio-Temporal Tensor Sketching via Adaptive Sampling](https://arxiv.org/pdf/2006.11943.pdf).

- **Tensor Singular Value Decomposition**

  - Canyi Lu, Jiashi Feng, Yudong Chen, Wei Liu, Zhouchen Lin, Shuicheng Yan (CVPR 2016). [Tensor Robust Principal Component Analysis: Exact Recovery of Corrupted
Low-Rank Tensors via Convex Optimization](https://canyilu.github.io/publications/2016-CVPR-TRPCA.pdf).

  - Canyi Lu, Jiashi Feng, Yudong Chen, Wei Liu, Zhouchen Lin, Shuicheng Yan (PAMI 2018). [Tensor Robust Principal Component Analysis with A New Tensor Nuclear Norm](https://arxiv.org/pdf/1804.03728.pdf).

- **Schatten p-norm minimization and its application**

  - [The Schatten p-norm on Rn](http://math.ntnu.edu.tw/~jschen/Papers/schatten-p-norm-JNCA.pdf).
  
  - Paper [t-Schatten-p norm for low-rank tensor recovery](https://doi.org/10.1109/JSTSP.2018.2879185) (2018): a new definition of tensor Schatten-p norm (t-Schatten-p norm) based on t-SVD.
  
  - Paper [Tensor p-shrinkage nuclear norm for low-rank tensor completion](https://arxiv.org/pdf/1907.04092v1.pdf) (2019): a new definition of tensor p-shrinkage nuclear norm (pTNN) is proposed based on tensor singular value decomposition (t-SVD).
  
  - Paper [Joint Schatten p-norm and  lp-norm robust matrix completion for missing value recovery](http://inside.mines.edu/~huawang/Papers/Journal/2013KAIS_pnorm.pdf) (2013).

- **Hankel matrix**

  - [Fast Hankel tensor–vector product and its application to exponential data fitting (2015)](http://www.math.hkbu.edu.hk/~wyding/paper/DingQiWei15.pdf).
  
  - [High Rank Matrix Completion with Side Information (AAAI 2018)](http://www.ccs.neu.edu/home/eelhami/publications/HRMC-SideInfo-AAAI18-Ehsan.pdf).
  
  - [Interpolation using Hankel tensor completion (2013)](http://dx.doi.org/10.1190/segam2013-0416.1).

- **Fourier analysis**

  - [Relationship between Singular Spectrum Analysis and Fourier analysis: Theory and application to the monitoring of volcanic activity](https://doi.org/10.1016/j.camwa.2010.05.028): This paper showed that SSA is related to Fourier analysis by using asymptotic properties of the eigenvalues of Toeplitz matrices.
  
- **Total variation**
  
  - Xu Han, Jiasong Wu, Lu Wang, Yang Chen, Lotfi Senhadji, Huazhong Shu (2014). [Linear Total Variation Approximate Regularized Nuclear Norm Optimization for Matrix Completion](https://projecteuclid.org/euclid.aaa/1425047781).
  
Deep Learning
---------------------

- **Attention Model**

  - Lilian Weng (2018). [Attention? Attention!](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html). Blog post.
  
  - [Attention Mechanism](https://blog.floydhub.com/attention-mechanism/). Blog post.
  
  - Fu et al. (CVPR 2019). [Dual Attention Network for Scene Segmentation](https://openaccess.thecvf.com/content_CVPR_2019/papers/Fu_Dual_Attention_Network_for_Scene_Segmentation_CVPR_2019_paper.pdf).
  
  - [GeoMAN: Multi-level Attention Networks for Geo-sensory Time Series Prediction](http://urban-computing.com/pdf/liang2018geoman.pdf).
  
  - Sinong Wang, Belinda Z. Li, Madian Khabsa, Han Fang, Hao Ma (2020). [Linformer: Self-Attention with Linear Complexity](https://arxiv.org/pdf/2006.04768.pdf).

Optimization Methods
----------------------

- **Majorization Minimization algorithm**
  
  - Kenneth Lange (2018). [Examples of MM Algorithms (slide)](https://hua-zhou.github.io/teaching/biostatm280-2018spring/slides/20-mm/deLeeuw.pdf).
  
  - David R. Hunter, Kenneth Lange (2004). [A Tutorial on MM Algorithms](http://www.leg.ufpr.br/~paulojus/EM/Tutorial%20on%20MM.pdf).
  
  - A paper [Exact minimum rank approximation via Schatten p-norm minimization](https://www.sciencedirect.com/science/article/pii/S0377042714001010) applied the Majorization Minimization algorithm to solve the Schatten p-norm minimization problem.
