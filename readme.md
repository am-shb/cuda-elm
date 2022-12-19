# CUDA Extreme Learning Machine
[Extreme learning machine](https://ieeexplore.ieee.org/abstract/document/1380068) (ELM) is a learning algorithm which randomly chooses the input weights and analytically determines the output weights of SLFNs. In theory, this algorithm tends to provide the best generalization performance at extremely fast learning speed.

This project uses the [DenseNet](https://arxiv.org/abs/1608.06993) network to generate image embeddings and feeds the results to an ELM which is implemented in the GPU using CUDA C++ and cuBLAS.

The model is trained and tested using Caltech101 and Caltech 256 datasets.

More information on the performance of the model is available in the report.pdf file.