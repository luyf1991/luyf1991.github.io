---
title: "Online Decentralized Leverage Score Sampling for Streaming Multidimensional Time Series"
collection: publications
permalink: /publication/2019-04-16-paper-title-number-8
excerpt: 'We propose a leverage score sampling (LSS) method for efficient online inference of the streaming vector autoregressive (VAR) model. We define the leverage score for the streaming VAR model so that the LSS method selects informative data points in real-time with statistical guarantees of parameter estimation efficiency. Moreover, our LSS method can be directly deployed in an asynchronous decentralized environment, e.g., a sensor network without a fusion center, and produce asynchronous consensus online parameter estimation over time. <br/><img src='/images/figure_paper2.png'><br/>'

date: 2019-04-16
venue: 'The 22nd International Conference on Artificial Intelligence and Statistics (AISTATS 2019)'
paperurl: 'http://ruixie7.github.io/files/AISTAT2019_v3.pdf'
citation: 'Rui Xie, Zengyan Wang, Shuyang Bai, Ping Ma, and Wenxuan Zhong. Online decentralized leveraging sampling for streaming multivariate time series. Accepted. The 22nd International Conference on Artificial Intelligence and Statistics (AISTATS 2019).'
---
Estimating the dependence structure of multidimensional time series data in real-time is challenging. With large volumes of streaming data, the problem becomes more difficult when the multidimensional data are collected asynchronously across distributed nodes, which motivates us to sample representative data points from streams. We propose a leverage score sampling (LSS) method for efficient online inference of the streaming vector autoregressive (VAR) model. We define the leverage score for the streaming VAR model so that the LSS method selects informative data points in real-time with statistical guarantees of parameter estimation efficiency. Moreover, our LSS method can be directly deployed in an asynchronous decentralized environment, e.g., a sensor network without a fusion center, and produce asynchronous consensus online parameter estimation over time. By exploiting the temporal dependence structure of the VAR model, the LSS method selects samples independently on each dimension and thus is able to update the estimation asynchronously. We illustrate the effectiveness of the LSS method in synthetic, gas sensor and seismic datasets. 

<br/><img src='/images/figure_paper2.png'><br/>

[Download paper here](http://ruixie7.github.io/files/AISTAT2019_v3.pdf)
 [Bibtex](http://ruixie7.github.io/files/Xie2019aistats.bib)
