# TribuoHdbscan
## Measurements and Comparisons of Tribuo Hdbscan, an HDBSCAN* implementation in Tribuo

An implementation of the HDBSCAN* clustering algorithm has been made in Tribuo [1], the Java machine learning library [Tribuo](https://tribuo.org/). Here is a link to the published article in the Applied Sciences journal: [An Implementation of the HDBSCAN\* Clustering Algorithm](https://doi.org/10.3390/app12052405). This implementation is based on the original HDBSCAN\* algorithm [2]. The project contains a set of notebooks which achieve two objectives:

1. Validate the correctness of the implementation's clustering and prediction results.
2. Compare the performance of Tribuo Hdbscan to a [reference Java implementation](http://lapad-web.icmc.usp.br/?portfolio_1=a-handful-of-experiments) and to the [Python module hdbscan](https://hdbscan.readthedocs.io/).

A tutorial describing how to use Tribuo Hdbscan is available [here](https://tribuo.org/learn/4.3/tutorials/clustering-hdbscan-tribuo-v4.html).

The Tribuo Hdbscan implementation is a complete, functional research project, and the code is included in the Tribuo code base. [Tribuo github](https://github.com/oracle/tribuo). These notebooks are up-to-date with the 4.3.0 release of Tribuo and there are no major enhancements planned for Tribuo Hdbscan in the forseeable future. The version of the Python module hdbscan used throughout these comparisons is 0.8.27. For the versions of these notebooks used in the published article mentioned above, use this [tag.](https://github.com/geoffreydstewart/TribuoHdbscan/tree/thesis)


[1] Stewart  G, Al-Khassaweneh M. An Implementation of the HDBSCAN* Clustering Algorithm. Applied Sciences. 2022; 12(5):2405.

[2] R. J. Campello, D. Moulavi, and J. Sander, "Density-based Clustering Based on Hierarchical Density Estimates," in Pacific-Asia Conference on Knowledge Discovery and Data Mining. Springer, 2013, pp. 160–172.
