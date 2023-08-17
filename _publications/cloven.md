---
title: "A Clustering-guided Contrastive Fusion for Multi-view Representation Learning"
authors: '<b>Guanzhou Ke</b>, Guoqing Chao, Xiaoli Wang, Chenyang Xu, Yongqi Zhu, and Yang Yu'
date: 2023-08-01
year: 2023
pubinfo: 'IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)'
arch: https://guanzhouk.top/images/cloven-arch.png
code: https://github.com/Guanzhou-Ke/cloven
pdf: https://arxiv.org/pdf/2212.13726.pdf
rank: "CCF B"
---

![Arch](https://ihades.cn/images/cloven-arch.png)

codeurl: https://github.com/Guanzhou-Ke/cloven
**Abstract:** Multi-view representation learning aims to extract comprehensive information from multiple sources. It has achieved significant success in applications such as video understanding and 3D rendering. However, how to improve the robustness and generalization of multi-view representations from unsupervised and incomplete scenarios remains an open question in this field. In this study, we discovered a positive correlation between the semantic distance of multi-view representations and the tolerance for data corruption. Moreover, we found that the information ratio of consistency and complementarity significantly impacts the performance of discriminative and generative tasks related to multi-view representations. Based on these observations, we propose an end-to-end CLustering-guided cOntrastiVE fusioN (CLOVEN) method, which enhances the robustness and generalization of multi-view representations simultaneously. To balance consistency and complementarity, we design an asymmetric contrastive fusion module. The module first combines all view-specific representations into a comprehensive representation through a scaling fusion layer. Then, the information of the comprehensive representation and view-specific representations is aligned via contrastive learning loss function, resulting in a view-common representation that includes both consistent and complementary information. We prevent the module from learning suboptimal solutions by not allowing information alignment between view-specific representations. We design a clustering-guided module that encourages the aggregation of semantically similar views. This action reduces the semantic distance of the view-common representation. We quantitatively and qualitatively evaluate CLOVEN on five datasets, demonstrating its superiority over 13 other competitive multi-view learning methods in terms of clustering and classification performance. In the data-corrupted scenario, our proposed method resists noise interference better than competitors. Additionally, the visualization demonstrates that CLOVEN succeeds in preserving the intrinsic structure of view-specific representations and improves the compactness of view-common representations. 


[\[PDF\]](https://arxiv.org/pdf/2212.13726.pdf) [\[CODE\]](https://github.com/Guanzhou-Ke/cloven)

Citation:

Bibtext:

```
@ARTICLE{10198322,
  author={Ke, Guanzhou and Chao, Guoqing and Wang, Xiaoli and Xu, Chenyang and Zhu, Yongqi and Yu, Yang},
  journal={IEEE Transactions on Circuits and Systems for Video Technology}, 
  title={A Clustering-guided Contrastive Fusion for Multi-view Representation Learning}, 
  year={2023},
  volume={},
  number={},
  pages={1-1},
  doi={10.1109/TCSVT.2023.3300319}}
```