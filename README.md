## Distribution Corruptation Robust SSL

- [Distributionally Robust Semi-Supervised Learning for People-Centric Sensing](https://arxiv.org/pdf/1811.05299.pdf) (AAAI 2019) - Authors: Kaixuan Chen, Lina Yao, Dalin Zhang, Xiaojun Chang, Guodong Long, Sen Wang
> This paper considers the distribution discrepancy between the labeled data and the unlabeled data, and align the feature distributions when the training data are distributed differently.
- [Semi-Supervised Learning by Augmented Distribution Alignment](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Semi-Supervised_Learning_by_Augmented_Distribution_Alignment_ICCV_2019_paper.pdf) (ICCV 2019) - Authors: Qin Wang, Wen Li, Luc Van Gool
> This paper proposes a method called Augmented Distribution Alignment to align the empirical distributions of labeled and unlabeled data to alleviate the sampling bias.

## Label Corruptation Robust SSL

- [Robust Semi-supervised Learning through Label Aggregation](http://iemppu.github.io/yan.pdf) (AAAI 2016) - Authors: Yan Yan, Zhongwen Xu, Ivor W. Tsang, Guodong Long, Yi Yang
> This paper considers the robustness of SSL algorithms when there exists label noise. The main idea is to adopt ensemble learning to aggregate multiple pseudo-labels.
- [Learning with Inadequate and Incorrect Supervision](https://arxiv.org/pdf/1902.07429.pdf) (ICDM 2017) - Authors: Chen Gong, Hengmin Zhang, Jian Yang, Dacheng Tao
- [Learning from Incomplete and Inaccurate Supervision](http://129.211.169.156/publication/kdd19pnu.pdf) (KDD 2019) - Authors: Zhen-Yu Zhang, Peng Zhao, Yuan Jiang and Zhi-Hua Zhou
- [Noise-robust semi-supervised learning via fast sparse coding](https://www.sciencedirect.com/science/article/pii/S0031320314003331) (Pattern Recognition 2015) - Authors: Zhiwu Lu, Liwei Wang
> This paper presents a noise-robust graph-based semi-supervised learning algorithm by using sparse encoding to deal with the problem of semi-supervised learning with noisy initial labels.
- [Unified Robust Semi-Supervised Variational Autoencoder](http://proceedings.mlr.press/v139/chen21a/chen21a.pdf) (ICML 2021) - Authors: Xu Chen
> This paper propose a noise-robust semi-supervised deep generative model by jointly tackling noisy labels and outliers simultaneously in a unified robust semi-supervised variational autoencoder

## Feature Corruptation Robust SSL

- [Robustness to Adversarial Perturbations in Learning from Incomplete Data](https://proceedings.neurips.cc/paper/2019/file/60ad83801910ec976590f69f638e0d6d-Paper.pdf) (NeurIPS 2019) - Authors: Amir Najaf, Shin-ichi Maeda, Masanori Koyama, Takeru Miyato
> This paper unifies Semi-Supervised Learning and Distributionally Robust Learning, and develops a generalization theory for the framework.

- [Unlabeled Data Improves Adversarial Robustness](https://papers.nips.cc/paper/2019/file/32e0bd1497aa43e02a42f47d9d6515ad-Paper.pdf) (NeurIPS 2019) - Authors: Yair Carmon, Aditi Raghunathan, Ludwig Schmidt, Percy Liang, John C. Duchi
> This paper shows a sample complexity gap between standard and robust classification and proves that unlabeled data bridges this gap: a simple semisupervised learning procedure (self-training) achieves high robust accuracy using the same number of labels required for achieving high standard accuracy. 

## Safe SSL

- [Unlabeled data: Now it helps, now it doesn’t](https://papers.nips.cc/paper/2008/file/07871915a8107172b3b5dc15a6574ad3-Paper.pdf) (NeurIPS 2008) - Authors: Aarti Singh, Robert D. Nowak, Xiaojin Zhu
> This paper develops a finite sample analysis that characterizes the value of unlabeled data and quantifies the performance improvement of SSL compared to supervised learning.
- [Scalable Semi-Supervised Aggregation of Classifiers](https://arxiv.org/pdf/1506.05790.pdf) (NeurIPS 2015) - Authors: Akshay Balsubramani, Yoav Freund
> This paper presents an algorithm that learns to aggregate the predictions of an ensemble of binary classifiers. It has no assumptions about the structure or origin of the predictions or labels and the accuracy is guaranteed to be at least that of the best classifier in the ensemble.
- [Contrastive Pessimistic Likelihood Estimation for Semi-Supervised Classification](https://arxiv.org/pdf/1503.00269.pdf) (TPAMI 2016) - Authors: Marco Loog
> This paper proposes a general way to perform semisupervised parameter estimation for likelihood-based classifiers for which, on the fulltraining set, the estimates are never worse than the supervised solution in terms of the log-likelihood.
