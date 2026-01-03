# GNN-based Fake News Detection
This includes the Pytorch-Geometric implementation of a series of Graph Neural Network (GNN) based fake news detection models.
All [GNN models](#user-guide) are implemented and evaluated under the User Preference-aware Fake News Detection ([UPFD](https://arxiv.org/pdf/2104.12259.pdf)) framework.
The fake news detection problem is instantiated as a graph classification task under the UPFD framework. 


The UPFD dataset and its example usage is also available at the PyTorch-Geometric official repo.

The following figure shows the UPFD framework including the dataset construction details 
You can refer to the [paper](https://arxiv.org/pdf/2005.00625.pdf) for more details about the dataset.

<p align="center">
    <br>
    <a href="https://github.com/safe-graph/GNN-FakeNews">
        <img src="https://github.com/safe-graph/GNN-FakeNews/blob/main/overview.png" width="1000"/>
    </a>
    <br>
<p>

  
All GNN-based fake news detection models are under the `\gnn_model` directory.
The implemented models are as follows:

* **[GNN-CL](https://arxiv.org/pdf/2007.03316.pdf)**: Han, Yi, Shanika Karunasekera, and Christopher Leckie. "Graph neural networks with continual learning for fake news detection from social media." arXiv preprint arXiv:2007.03316 (2020).
* **[GCNFN](https://arxiv.org/pdf/1902.06673.pdf)**: Monti, Federico, Fabrizio Frasca, Davide Eynard, Damon Mannion, and Michael M. Bronstein. "Fake news detection on social media using geometric deep learning." arXiv preprint arXiv:1902.06673 (2019).
* **[BiGCN](https://arxiv.org/pdf/2001.06362.pdf)**: Bian, Tian, Xi Xiao, Tingyang Xu, Peilin Zhao, Wenbing Huang, Yu Rong, and Junzhou Huang. "Rumor detection on social media with bi-directional graph convolutional networks." In Proceedings of the AAAI Conference on Artificial Intelligence, vol. 34, no. 01, pp. 549-556. 2020.
* **[UPFD-GCN](https://arxiv.org/pdf/1609.02907.pdf)**: Kipf, Thomas N., and Max Welling. "Semi-supervised classification with graph convolutional networks." arXiv preprint arXiv:1609.02907 (2016).
* **[UPFD-GAT](https://arxiv.org/pdf/1710.10903.pdf)**: Veličković, Petar, Guillem Cucurull, Arantxa Casanova, Adriana Romero, Pietro Lio, and Yoshua Bengio. "Graph attention networks." arXiv preprint arXiv:1710.10903 (2017).
* **[UPFD-SAGE](https://cs.stanford.edu/people/jure/pubs/graphsage-nips17.pdf)**: Hamilton, William L., Rex Ying, and Jure Leskovec. "Inductive representation learning on large graphs." arXiv preprint arXiv:1706.02216 (2017).





