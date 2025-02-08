## Welcome to GitHub Pages of BruSLeAttack

Reproduce our results: [GitHub](https://github.com/afsharshamsi/Bella/Bella.github.io)

Check out our paper: [BruSLeAttack: A Query-Efficient Score-Based Black-Box Sparse Adversarial Attack](https://openreview.net/forum?id=PAfnMGXief)


Cite our research: 
```
@inproceedings{Vo2024,
    title = {BruSLeAttack: A Query-Efficient Score-Based Black-Box Sparse Adversarial Attack},
    year = {2024},
    booktitle = {International Conference on Learning Representations (ICLR)},
    author = Viet Quoc Vo and Ehsan Abbasnejad and Damith C. Ranasinghe},
}
```

#### ABSTRACT

We study the unique and less-well understood problem of generating sparse adversarial attacks simply based on observing the score-based replies to model queries. Sparse attacks aim to discover a minimum number—the l0 bounded—perturbations to model inputs to craft adversarial examples and misguide model decisions. But, in contrast to query-based dense attack counterparts against black-box models, 6 constructing sparse adversarial perturbations, even when models serve confidence score information to queries in a score-based setting, is non-trivial. Because such an attack leads to: i) an NP-hard problem; and ii) a non-differentiable search space. We develop the BruSLeAttack—a new algorithm for the problem and evaluate against Convolutional Neural Networks, Vision Transformers, recent Stylized ImageNet models, defense methods and Machine Learning as a Service (MLaaS) offerings exemplified by Google Cloud Vision. The proposed attack scales to achieve state-of-the-art attack success rates and query efficiency on standard computer visions tasks such as ImageNet across various models. Importantly, our highly query-efficient algorithm facilitates faster evaluation of model vulnerabilities and raises questions regarding the safety, security and reliability of deployed systems.



