---
title: "Finding separatrices of dynamical flows with Deep Koopman Eigenfunctions" 
date: 2025-05-28
tags: []
author: ["Kabir V. Dabholkar","Omri Barak"]
description: "A numerical method utilising neural networks and Koopman theory to find separatrices of dynamical systems." 
summary: "" 
cover:
    image: "finding_separatrices.png"
    alt: "Find"
    relative: true
editPost:
    URL: "https://arxiv.org/abs/2505.15231"
    Text: "arxiv"

---

![Finding separatrices of dynamical flows with Deep Koopman Eigenfunctions](finding_separatrices.png)


---

### Abstract

Many natural systems, including neural circuits involved in decision making, can be modeled as high-dimensional dynamical systems with multiple stable states. While existing analytical tools primarily describe behavior near stable equilibria, characterizing separatrices -- the manifolds that delineate boundaries between different basins of attraction -- remains challenging, particularly in high-dimensional settings. Here, we introduce a numerical framework leveraging Koopman Theory combined with Deep Neural Networks to effectively characterize separatrices. Specifically, we approximate Koopman Eigenfunctions (KEFs) associated with real positive eigenvalues, which vanish precisely at the separatrices. Utilizing these scalar KEFs, optimization methods efficiently locate separatrices even in complex systems. We demonstrate our approach on synthetic benchmarks, ecological network models, and recurrent neural networks trained on neuroscience-inspired tasks. Moreover, we illustrate the practical utility of our method by designing optimal perturbations that can shift systems across separatrices, enabling predictions relevant to optogenetic stimulation experiments in neuroscience.

---

##### Citation 

Dabholkar, Kabir V., and Omri Barak. "Finding separatrices of dynamical flows with Deep Koopman Eigenfunctions." arXiv preprint arXiv:2505.15231 (2025).

```BibTeX
@article{dabholkar2025finding,
  title={Finding separatrices of dynamical flows with Deep Koopman Eigenfunctions},
  author={Dabholkar, Kabir V and Barak, Omri},
  journal={arXiv preprint arXiv:2505.15231},
  year={2025}
}
```
