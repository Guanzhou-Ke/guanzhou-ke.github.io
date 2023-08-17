---
title: "Disentangling Multi-view Representations Beyond Inductive Bias"
authors: '<b>Guanzhou Ke</b>, Yang Yu, Guoqing Chao, Xiaoli Wang, Chenyang Xu, and Shengfeng He'
date: 2023-07-26
pubinfo: 'The 31st ACM International Conference on Multimedia (ACM MM 2023)'
code: https://github.com/Guanzhou-Ke/DMRIB
arch: https://guanzhouk.top/images/dmrib-arch.png
pdf: https://guanzhouk.top/files/dmrib.pdf
rank: "CCF A"
---

![Arch](https://ihades.cn/images/dmrib-arch.png)


**Abstract:** Multi-view (or -modality) representation learning aims to understand the relationships between different view representations. Existing methods disentangle multi-view representations into consistent and view-specific representations by introducing strong inductive biases, which can limit their generalization ability. In this paper, we propose a novel multi-view representation disentangling method that aims to go beyond inductive biases, ensuring both interpretability and generalizability of the resulting representations. Our method is based on the observation that discovering multi-view consistency in advance can determine the disentangling information boundary, leading to a decoupled learning objective. We also found that the consistency can be easily extracted by maximizing the transformation invariance and clustering consistency between views. These observations drive us to propose a two-stage framework. In the first stage, we obtain multi-view consistency by training a consistent encoder to produce semantically-consistent representations across views as well as their corresponding pseudo-labels. In the second stage, we disentangle specificity from comprehensive representations by minimizing the upper bound of mutual information between consistent and comprehensive representations. Finally, we reconstruct the original data by concatenating pseudo-labels and view-specific representations. Our experiments on four multi-view datasets demonstrate that our proposed method outperforms 12 comparison methods in terms of clustering and classification performance. The visualization results also show that the extracted consistency and specificity are compact and interpretable. 


[\[PDF\]](https://ihades.cn/files/dmrib.pdf) [\[CODE\]](https://github.com/Guanzhou-Ke/DMRIB)

Citation:

Plain:

```
Guanzhou Ke, Yang Yu, Guoqing Chao, Xiaoli Wang, Chenyang Xu,
and Shengfeng He. 2023. Disentangling Multi-view Representations Be-
yond Inductive Bias. In Proceedings of the 31st ACM International Conference
on Multimedia (MM ’23), October 29–November 3, 2023, Ottawa, ON, Canada.
ACM, New York, NY, USA, 9 pages. https://doi.org/10.1145/3581783.3611794
```

Bibtext:

```
@inproceedings{ke2023dmrib,
  title={Disentangling Multi-view Representations Beyond Inductive Bias},
  author={Guanzhou Ke, Yang Yu, Guoqing Chao, Xiaoli Wang, Chenyang Xu, and Shengfeng He},
  booktitle={In Proceedings of the 31st ACM International Conference on Multimedia},
  year={2023},
  organization={ACM}
}
```