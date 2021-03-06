This repository presents a notebook to reproduce the experiments of the preprint paper ["Using Laplacian Spectrum as Graph Feature Representation"](https://arxiv.org/abs/1912.00735).

It presents the theoretical explanation for the good results obtained in the experimental workshop paper ["A simple baseline algorithm for graph classification"](https://arxiv.org/abs/1810.09155) ([and its Github page](https://github.com/edouardpineau/A-simple-baseline-algorithm-for-graph-classification)).

### Abstract

Graphs possess exotic features like variable size and absence of natural ordering of the nodes that make them difficult to analyze and compare. To circumvent this problem and learn on graphs, graph feature representation is required. A good graph representation must satisfy the preservation of structural information, with two particular key attributes: consistency under deformation and invariance under isomorphism. While state-of-the-art methods seek such properties with powerful graph neural-networks, we propose to leverage a simple graph feature: the graph Laplacian spectrum (GLS). We first remind and show that GLS satisfies the aforementioned key attributes, using a graph perturbation approach. In particular, we derive bounds for the distance between two GLS that are related to the \textit{divergence to isomorphism}, a standard computationally expensive graph divergence. We finally experiment GLS as graph representation through consistency tests and classification tasks, and show that it is a strong graph feature representation baseline.


### Datasets

All datasets can be found [here](https://ls11-www.cs.tu-dortmund.de/staff/morris/graphkerneldatasets). The results printed within the notebook are obtained with 5 molecular datasets.
