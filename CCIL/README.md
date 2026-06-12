<div align="center">

# CCIL

Causal Clothes-Invariant Feature Learning for Cloth-Changing Person Re-ID

[![Venue](https://img.shields.io/badge/IEEE%20TCSVT-2026-7a1fa2?style=flat-square)](https://ieeexplore.ieee.org/document/11552757)
[![Paper](https://img.shields.io/badge/Paper-arXiv-b31b1b?style=flat-square)](https://arxiv.org/abs/2305.06145)

</div>

> [!NOTE]
> 👕 面向换衣行人重识别，通过因果干预建模 \(P(Y|do(X))\)，缓解训练集中的服装捷径问题，学习更稳定的服装不变身份特征。

<p align="center">
  <img src="./封面.png" alt="CCIL preview" width="92%">
</p>

## ✅ Overview

CCIL 针对 cloth-changing person re-identification 中服装与身份标签的虚假相关问题，构建 Confounder Dictionary、Intervention Module 和 Disentangle Regularization，将常规似然学习 \(P(Y|X)\) 转向因果干预学习 \(P(Y|do(X))\)，从而降低模型对服装线索的依赖。

## 🔗 Quick Links

| Type | Link |
| --- | --- |
| 📄 Paper | [Causal Clothes-Invariant Feature Learning for Cloth-Changing Person Re-ID](https://arxiv.org/abs/2305.06145) |

## 📚 Citation

```bibtex
@article{li2026causal,
  title={Causal Clothes-Invariant Feature Learning for Cloth-Changing Person Re-ID},
  author={Li, Xulin and Lu, Yan and Liu, Bin and Li, Jiaze and Liu, Yating and Chu, Qi and Ye, Mang and Ouyang, Wanli and Yu, Nenghai},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2026},
  publisher={IEEE}
}
```
