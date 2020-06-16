---
layout: page
title:  Problems
cover:  false
menu:   true
order:  1
---

> _I would have written a shorter letter, but I did not have the time._
>
> ---Blaise Pascal

Multivariate time series imputation
---------

- Non-random missing (missing not at random in matrix/tensor.)

- Blockouts (Missing values are occured in some consecutive time points for all time series. One recent work is [HKMF-T: Recover from blackouts in tagged time series with Hankel matrix factorization](https://ieeexplore.ieee.org/document/8979178).)

- Count valued data (There are many count valued data, e.g., passenger/traffic flow. But how to develop any machine/statistical learning model for them? One online imputation work is [Online tensor decomposition and imputation for count data](http://www2.ece.rochester.edu/~gmateosb/pubs/tensor/tensor_DSW19_Slides.pdf).)


Multivariate time series forecasting
---------

- High-dimensional data (One example is [web traffic time series forecasting
](https://www.kaggle.com/c/web-traffic-time-series-forecasting/data) which consists of approximately 145k time series, and the first place solution is available at [https://github.com/Arturus/kaggle-web-traffic](https://github.com/Arturus/kaggle-web-traffic). Another example is using Diffusion Convolutional Recurrent Neural Network (DCRNN) to forecast the traffic of the entire California highway network with 11,160 traffic sensor locations simultaneously, and the Python code is available at [https://github.com/liyaguang/DCRNN](https://github.com/liyaguang/DCRNN).)

  - [High-dimensional multivariate forecasting with low-rank Gaussian copula processes](https://arxiv.org/pdf/1910.03002.pdf): Is it really scalable to high-dimensional multivariate time series forecasting?

- Non-stationary signals (One recent work is [Shape and time distortion loss for training deep time series forecasting models](https://papers.nips.cc/paper/8672-shape-and-time-distortion-loss-for-training-deep-time-series-forecasting-models.pdf) appeared in [NeurIPS 2019](https://papers.nips.cc/paper/8672-shape-and-time-distortion-loss-for-training-deep-time-series-forecasting-models).)

- Short time series data (One intuitive example is daily passenger flow at railway station during special periods like Chinese New Year (about two to three weeks). How to apply machine learning models like [Hankel structured low rank matrix completion](http://homepages.vub.ac.be/~imarkovs/talks/cambridge11.pdf) to forecast short time series? How to generalize it to multivariate time series cases?)

- Missing data.

- Multi-dimensional data (One excellent example is human mobility flow, it has origin, destination, and time dimensions.)
