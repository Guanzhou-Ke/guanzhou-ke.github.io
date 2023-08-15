---
title: "CONAN: Contrastive Fusion Networks for Multi-view Clustering"
collection: publications
permalink: /publications/conan-contrastive-fusion-networks-for-multi-view-clustering
excerpt: '**Guanzhou Ke**, Zhiyong Hong, Zhiqiang Zeng, Zeyi Liu, Yangjie Sun, and Yannan Xie'
date: 2021-12-01
venue: 'IEEE International Conference on Big Data (Big Data)'
codeurl: https://github.com/Guanzhou-Ke/conan
---

![Arch](https://ihades.cn/images/conan-arch.png)


**Abstract:** With the development of big data, deep learning has made remarkable progress on multi-view clustering. Multi-view fusion is a crucial technique for the model obtaining a common representation. However, existing literature adopts shallow fusion strategies, such as weighted-sum fusion and concatenating fusion, which fail to capture complex information from multiple views. In this paper, we propose a novel fusion technique, entitled contrastive fusion, which can extract consistent representations from multiple views and maintain the characteristic of view-specific representations. Specifically, we study multi-view alignment from an information bottleneck perspective and introduce an intermediate variable to align each view-specific representation. Furthermore, we leverage a single-view clustering method as a predictive task to ensure the contrastive fusion is working. We integrate all components into an unified framework called CONtrAstive fusion Network (CONAN). Experiment results on five multi-view datasets demonstrate that CONAN outperforms state-of-the-art methods.


[\[PDF\]](https://ihades.cn/files/conan.pdf) [\[CODE\]](https://github.com/Guanzhou-Ke/conan)

Citation:

```
@inproceedings{ke2021conan,
  title={CONAN: Contrastive Fusion Networks for Multi-view Clustering},
  author={Ke, Guanzhou and Hong, Zhiyong and Zeng, Zhiqiang and Liu, Zeyi and Sun, Yangjie and Xie, Yannan},
  booktitle={2021 IEEE International Conference on Big Data (Big Data)},
  pages={653--660},
  year={2021},
  organization={IEEE}
}
```