---
title: "A Faster Sampling Algorithm for Spherical k-means"
collection: publications
permalink: /anup-publication/A-Faster-Sampling-Algorithm-for-Spherical-k-means
excerpt: ''
date: 2018-05-10
venue: 'ACML'
citation: Pratap, R., Deshmukh, A., Nair, P., & Dutt, T. (2018, November). A Faster Sampling Algorithm for Spherical $k$-means. In Asian Conference on Machine Learning (pp. 343-358).

---

**Abstract:** The Spherical k-means algorithm proposed by [Dhillon and Modha, 2001](https://doi.org/10.1023/A:1007612920971) is a popular algorithm for clustering high dimensional datasets. Although their algorithm is simple and easy to implement, a drawback of the same is that it doesn’t provide any provable guarantee on the clustering result. [Endo and Miyamoto, 2015](https://doi.org/10.1007/978-3-319-23240-9_9) suggest an adaptive sampling based algorithm (Spherical k-means++) which gives near optimal results, with high probability. However, their algorithm requires k sequential passes over the entire dataset, which may not be feasible when the dataset and/or the values of k are large. 

In this work, we propose a Markov chain based sampling algorithm that takes only one pass over the data, and gives close to optimal clustering similar to Spherical k-means++, i.e., a faster algorithm while maintaining almost the same approximation. We present a theoretical analysis of the algorithm, and complement it with rigorous experiments on real-world datasets. We proved that, with our approach the computational complexity in SPKM++ can be decreased while retaining the clustering results. Our proposed algorithm is simple and easy to implement, and can be easily adopted in practice.

**Link to the paper:** [SPKM](http://proceedings.mlr.press/v95/pratap18a.html), Proceedings of Machine Learning Research (PMLR) - [Asian Conference on Machine Learnig (ACML) 2018](http://www.acml-conf.org/2018/).

**Paper presentation:** [Slides](http://Anup-Deshmukh.github.io/files/ACML_slides.pdf)


