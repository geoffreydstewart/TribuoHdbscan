# TribuoHdbscan
## Measurements and Comparisons of Tribuo Hdbscan, an HDBSCAN* implementation in Tribuo

An implementation of the HDBSCAN* clustering algorithm has been made in Tribuo [1], the Java machine learning library [Tribuo](https://tribuo.org/). Here is a link to the published article in the Applied Sciences journal: [An Implementation of the HDBSCAN\* Clustering Algorithm](https://doi.org/10.3390/app12052405). This implementation is based on the original HDBSCAN\* algorithm [2]. The project contains a set of notebooks which achieve two objectives:

1. Validate the correctness of the implementation's clustering and prediction results.
2. Compare the performance of Tribuo Hdbscan to a [reference Java implementation](http://lapad-web.icmc.usp.br/?portfolio_1=a-handful-of-experiments) and to the [Python module hdbscan](https://hdbscan.readthedocs.io/).

A tutorial describing how to use Tribuo Hdbscan is available [here](https://tribuo.org/learn/4.2/tutorials/clustering-hdbscan-tribuo-v4.html).

The Tribuo Hdbscan implementation is an ongoing research project, and the code is included in the Tribuo code base. [Tribuo github](https://github.com/geoffreydstewart/tribuo).


[1] Stewart  G, Al-Khassaweneh M. An Implementation of the HDBSCAN* Clustering Algorithm. Applied Sciences. 2022; 12(5):2405.

[2] R. J. Campello, D. Moulavi, and J. Sander, "Density-based Clustering Based on Hierarchical Density Estimates," in Pacific-Asia Conference on Knowledge Discovery and Data Mining. Springer, 2013, pp. 160–172.
