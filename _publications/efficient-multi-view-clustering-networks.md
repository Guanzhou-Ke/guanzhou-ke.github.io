---
title: "Efficient Multi-view Clustering Networks"
collection: publications
permalink: /publication/efficient-multi-view-clustering-networks
excerpt: '**Guanzhou Ke**, Zhiyong Hong, Wenhua Yu, Xin Zhang, and Zeyi Liu'
date: 2022-01-01
venue: 'Applied Intelligence Springer'
---

![Arch](https://ihades.cn/images/emc-arch.png)


**Abstract:**\ In the last decade, deep learning has made remarkable progress on multi-view clustering (MvC), with existing literature adopting a broad target to guide the network learning process, such as minimizing the reconstruction loss. However, despite this strategy being effective, it lacks efficiency. Hence, in this paper, we proposed a novel framework, entitled Efficient Multi-view Clustering Networks (EMC-Nets), which guarantees the network’s learning efficiency and produces a common discriminative representation from multiple sources. Specifically, we developed an alternating process, involving an approximation and an instruction process, which effectively stimulate the process of multi-view feature fusion to force network to learn a discriminative common representation. The approximation process employs a standard clustering algorithm, i.e., k-means, to generate pseudo labels corresponding to the current common representation, and then it leverages the pseudo labels to force the network to approximate a reasonable cluster distribution. Considering the instruction process, it aims to provide a correct learning direction for the approximation process and prevent the network from obtaining trivial solutions. Experiment results on four real-world datasets demonstrate that the proposed method outperforms state-of-the-art methods. 

[\[PDF\]](https://ihades.cn/files/emc-nets.pdf) [\[CODE\]](https://github.com/Guanzhou-Ke/EMC-Nets)

Citation:

```
@article{ke2022efficient,
  title={Efficient multi-view clustering networks},
  author={Ke, Guanzhou and Hong, Zhiyong and Yu, Wenhua and Zhang, Xin and Liu, Zeyi},
  journal={Applied Intelligence},
  pages={1--17},
  year={2022},
  publisher={Springer}
}
```