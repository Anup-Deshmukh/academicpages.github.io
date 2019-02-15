---
title: "A Faster Sampling Algorithm for Spherical k-means"
collection: publications
permalink: /publication/2018-10-01-paper-title-number-3
excerpt: ''
date: 2018-05-10
venue: 'ACML'
---
The Spherical k-means (SPKM) is an important problem in unsupervised learning. It is similar to the k-means clustering problem and uses cosine similarity as a similarity/distance measure instead of euclidean distance. Although the SPKM algorithm is simple and efficient, it depends on the initial values of the k cluster centers. The task of locating k initial cluster centers is important in obtaining high quality clustering. 

The Spherical k-means algorithm proposed by [Dhillon and Modha, 2001](https://doi.org/10.1023/A:1007612920971) is a popular algorithm for clustering high dimensional datasets. Although their algorithm is simple and easy to implement, a drawback of the same is that it doesn’t provide any provable guarantee on the clustering result. [Endo and Miyamoto, 2015](https://doi.org/10.1007/978-3-319-23240-9_9) suggest an adaptive sampling based algorithm (Spherical k-means++) which gives near optimal results, with high probability. However, their algorithm requires k sequential passes over the entire dataset, which may not be feasible when the dataset and/or the values of k are large. 

In this work, we propose a Markov chain based sampling algorithm that takes only one pass over the data, and gives close to optimal clustering similar to Spherical k-means++, i.e., a faster algorithm while maintaining almost the same approximation. We present a theoretical analysis of the algorithm, and complement it with rigorous experiments on real-world datasets. We proved that, with our approach the computational complexity in SPKM++ can be decreased while retaining the clustering results. Our proposed algorithm is simple and easy to implement, and can be easily adopted in practice.

Link to the paper: [SPKM](http://proceedings.mlr.press/v95/pratap18a.html), Proceedings of Machine Learning Research (PMLR) - [Asian Conference on Machine Learnig (ACML) 2018](http://www.acml-conf.org/2018/).

APA citation: Pratap, R., Deshmukh, A., Nair, P., & Dutt, T. (2018, November). A Faster Sampling Algorithm for Spherical $k$-means. In Asian Conference on Machine Learning (pp. 343-358).

MLA citation: Pratap, Rameshwar, et al. "A Faster Sampling Algorithm for Spherical $ k $-means." Asian Conference on Machine Learning. 2018.



