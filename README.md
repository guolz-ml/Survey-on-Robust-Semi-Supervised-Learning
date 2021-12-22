## Robust SSL to Feature Distribution MisMatch

- [Distributionally Robust Semi-Supervised Learning for People-Centric Sensing](https://arxiv.org/pdf/1811.05299.pdf) (AAAI 2019) - Authors: Kaixuan Chen, Lina Yao, Dalin Zhang, Xiaojun Chang, Guodong Long, Sen Wang
> This paper considers the distribution discrepancy between the labeled data and the unlabeled data, and align the feature distributions when the training data are distributed differently.
- [Semi-Supervised Learning by Augmented Distribution Alignment](https://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Semi-Supervised_Learning_by_Augmented_Distribution_Alignment_ICCV_2019_paper.pdf) (ICCV 2019) - Authors: Qin Wang, Wen Li, Luc Van Gool
> This paper proposes a method called Augmented Distribution Alignment to align the empirical distributions of labeled and unlabeled data to alleviate the sampling bias.

- [On semi-supervised linear regression in covariate shift problems. The Journal of Machine Learning](https://www.jmlr.org/papers/volume16/ryan15a/ryan15a.pdf) (JMLR 2015) - Authors: Kenneth Joseph Ryan, Mark Vere Culp
> 

- [RECORD: Resource Constrained Semi-Supervised Learning
under Distribution Shif](https://cs.nju.edu.cn/liyf/paper/kdd20-record.pdf) (KDD 2020) - Authors: Lan-Zhe Guo, Zhi Zhou, Yu-Feng Li.
> This paper focuses on the problem that unlabeled data arrives in a data stream and the distribution changes over time. The paper proposed an influence function based example selection strategy that can maintain examples that are most helpful for current and future distribution.

## Robust SSL to Label Distribution MisMatch
- [Semi-Supervised Learning of Class Balance
under Class-Prior Change by Distribution Matching](https://icml.cc/Conferences/2012/papers/437.pdf) (ICML 2014) - Authors: Marthinus Christoffel du Plessis, Masashi Sugiyama.
> This paper proposes to estimate the class ratio in the unlabeled dataset by matching probability distributions of
labeled and unlabeled input data.



## Label Corruptation Robust SSL

- [Robust Semi-supervised Learning through Label Aggregation](http://iemppu.github.io/yan.pdf) (AAAI 2016) - Authors: Yan Yan, Zhongwen Xu, Ivor W. Tsang, Guodong Long, Yi Yang
> This paper considers the robustness of SSL algorithms when there exists label noise. The main idea is to adopt ensemble learning to aggregate multiple pseudo-labels.
- [Learning with Inadequate and Incorrect Supervision](https://arxiv.org/pdf/1902.07429.pdf) (ICDM 2017) - Authors: Chen Gong, Hengmin Zhang, Jian Yang, Dacheng Tao
- [Learning from Incomplete and Inaccurate Supervision](http://129.211.169.156/publication/kdd19pnu.pdf) (KDD 2019) - Authors: Zhen-Yu Zhang, Peng Zhao, Yuan Jiang and Zhi-Hua Zhou
- [Noise-robust semi-supervised learning via fast sparse coding](https://www.sciencedirect.com/science/article/pii/S0031320314003331) (Pattern Recognition 2015) - Authors: Zhiwu Lu, Liwei Wang
> This paper presents a noise-robust graph-based semi-supervised learning algorithm by using sparse encoding to deal with the problem of semi-supervised learning with noisy initial labels.
- [Unified Robust Semi-Supervised Variational Autoencoder](http://proceedings.mlr.press/v139/chen21a/chen21a.pdf) (ICML 2021) - Authors: Xu Chen
> This paper propose a noise-robust semi-supervised deep generative model by jointly tackling noisy labels and outliers simultaneously in a unified robust semi-supervised variational autoencoder

-[Semi-supervised Learning from Crowds Using Deep Generative Models](https://eprints.lib.hokudai.ac.jp/dspace/bitstream/2115/67695/1/aaai2018.pdf) (AAAI 2018) - Authors: Atarashi, Kyohei; Oyama, Satoshi; Kurihara, Masahito. 
> This paper assumes the data labeled are obtained by crowdsourcing.

-[Boosting Semi-Supervised Face Recognition with Noise Robustness](https://arxiv.org/abs/2105.04431)
## Feature Corruptation Robust SSL

- [Robustness to Adversarial Perturbations in Learning from Incomplete Data](https://proceedings.neurips.cc/paper/2019/file/60ad83801910ec976590f69f638e0d6d-Paper.pdf) (NeurIPS 2019) - Authors: Amir Najaf, Shin-ichi Maeda, Masanori Koyama, Takeru Miyato
> This paper unifies Semi-Supervised Learning and Distributionally Robust Learning, and develops a generalization theory for the framework.

- [Unlabeled Data Improves Adversarial Robustness](https://papers.nips.cc/paper/2019/file/32e0bd1497aa43e02a42f47d9d6515ad-Paper.pdf) (NeurIPS 2019) - Authors: Yair Carmon, Aditi Raghunathan, Ludwig Schmidt, Percy Liang, John C. Duchi
> This paper shows a sample complexity gap between standard and robust classification and proves that unlabeled data bridges this gap: a simple semisupervised learning procedure (self-training) achieves high robust accuracy using the same number of labels required for achieving high standard accuracy. 

-[Toward Adversarial Robustness via Semi-supervised Robust Training](https://arxiv.org/pdf/2003.06974.pdf) - Authors: Yiming Li, Baoyuan Wu, Yan Feng, Yanbo Fan, Yong Jiang, Zhifeng Li, Shutao Xia
> This paper proposes a robust training method that can be extended to semi-supervised mode to enhance the adversarial robustness.

-[DeHiB: Deep Hidden Backdoor Attack on Semi-supervised Learning via Adversarial Perturbation](https://ojs.aaai.org/index.php/AAAI/article/view/17266/17073) (AAAI 2021) - Authors: Zhicong Yan, Gaolei Li, Yuan TIan, Jun Wu, Shenghong Li, Mingzhe Chen, H. Vincent Poor
> This paper proposes a deep hidden backdoor (DeHiB) attack for SSL-based systems. In contrast to the conventional
attacking methods, the DeHiB can feed malicious unlabeled training data to the semi-supervised learner so as to enable the SSL model to output premeditated results.

-[Tangent-Normal Adversarial Regularization for Semi-supervised Learning](https://openaccess.thecvf.com/content_CVPR_2019/papers/Yu_Tangent-Normal_Adversarial_Regularization_for_Semi-Supervised_Learning_CVPR_2019_paper.pdf) (CVPR 2019) - Authors: Bing Yu, Jingfeng Wu, Jinwen Ma, Zhanxing Zhu
> This paper proposes a new regularization technique for semi-supervised learning than can improve the robustness of SSL to noisy features.

-[Improving Adversarial Robustness via Unlabeled Out-of-Domain Data](http://proceedings.mlr.press/v130/deng21b/deng21b.pdf) (AISTATS 2021) - Authors: Zhun Deng, Linjun Zhang, Amirata Ghorbani, James Zou
> This paper show how to leverage out-of-domain data to improve adversarial robustness when some structural information, such as sparsity, is shared between labeled and unlabeled domains.

-[Adversarial Variational Embedding for Robust Semi-supervised Learning](https://dl.acm.org/doi/pdf/10.1145/3292500.3330966) (KDD 2019) - Authors: Xiang Zhang, Lina Yao, Feng Yuan
> This paper proposes an Adversarial Variational Embedding (AVAE) framework for robust semi-supervised learning by leveraging both the advantage of GAN as a high quality generative model and VAE as a posterior distribution learner.

-[Mixing Up Real Samples and Adversarial Samples for Semi-Supervised Learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9207038) (IJCNN 2020) -  Authors: Yun Ma, Xudong Mao, Yangbin Chen, Qing Li
> This paper propose a new regularization for semi-supervised learning that can improve the adversarial robustness of SSL algorithms.

-[Poisoning the Unlabeled Dataset of Semi-Supervised Learning](https://arxiv.org/pdf/2105.01622.pdf) - Authors: Nicholas Carlini
> This paper studies the ability for an adversary to poison semi-supervised learning algorithms by injecting unlabeled data.
 
## Relation Corruptation Robust SSL

- [Robust Semi-Supervised Learning on Multiple Networks with Noise](https://www.andrew.cmu.edu/user/lakoglu/pubs/18-pakdd-imune.pdf) (PAKDD 2019) - Authors: Junting Ye, Leman Akoglu
>This paper studies the problem that graph-based semi-supervised learning with noisy and/or irrelevant relations in the graph structure.

- [Unlabeled data: Now it helps, now it doesn’t](https://papers.nips.cc/paper/2008/file/07871915a8107172b3b5dc15a6574ad3-Paper.pdf) (NeurIPS 2008) - Authors: Aarti Singh, Robert D. Nowak, Xiaojin Zhu
> This paper develops a finite sample analysis that characterizes the value of unlabeled data and quantifies the performance improvement of SSL compared to supervised learning.

- [Scalable Semi-Supervised Aggregation of Classifiers](https://arxiv.org/pdf/1506.05790.pdf) (NeurIPS 2015) - Authors: Akshay Balsubramani, Yoav Freund
> This paper presents an algorithm that learns to aggregate the predictions of an ensemble of binary classifiers. It has no assumptions about the structure or origin of the predictions or labels and the accuracy is guaranteed to be at least that of the best classifier in the ensemble.

- [Contrastive Pessimistic Likelihood Estimation for Semi-Supervised Classification](https://arxiv.org/pdf/1503.00269.pdf) (TPAMI 2016) - Authors: Marco Loog
> This paper proposes a general way to perform semisupervised parameter estimation for likelihood-based classifiers for which, on the fulltraining set, the estimates are never worse than the supervised solution in terms of the log-likelihood.
