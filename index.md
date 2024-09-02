---
layout: post
---


<div class="home">
  <div class="site-header-container">
    <div class="scrim">
      <header class="site-header">
        <div class="subimg">
        <img src="assets/me.jpg">
        </div>
        <h3 class="title">{{ site.title }}</h3>
      </header>
    </div>
  </div>
</div>

I am an associate distinguished researcher at [NTT](https://www.rd.ntt/e/cds/) and a Ph.D student at Kyoto University ([Kashima Lab.](http://www.ml.ist.i.kyoto-u.ac.jp/en/)).
My research interests are machine learning with synthetic data, generative models, distribution shifts, self-supervised learning, and semi-supervised learning.

# Updates
* **[2024/4/1]** I'm happy to annouce that I have been promoted to associate distinguished researcher in NTT!
* **[2024/3/18]** Our two papers [**Test-Time Similarity Modification for Person Re-Identification Toward Temporal Distribution Shift**](https://arxiv.org/abs/2403.14114) and [**Test-Time Adaptation Meets Image Enhancement: Improving Accuracy via Uncertainty-Aware Logit Switching**](https://arxiv.org/abs/2403.17423) have been accepted to IJCNN 2024!
* **[2024/2/26]** Our paper [**Adaptive Random Feature Regularization on Fine-tuning Deep Neural Networks**](https://arxiv.org/abs/2403.10097) has been accepted to CVPR 2024! We propose a simple yet effective fine-tuning method by penalizing feature extractors with randome reference vectors generated from adaptive class-conditional priors.
* **[2023/11/23]** Our preprint [**On the Limitation of Diffusion Models for Synthesizing Training Datasets**](https://arxiv.org/abs/2311.13090) appeared in arXiv! We analyzed diffusion models with various perspectives and found that modern diffusion models have a limitation on the ability to replicate datasets in terms of accuracy when the synthetic samples are used for training classifiers. This work will be presented at [NeurIPS 2023 SyntheticData4ML Workshop](https://www.syntheticdata4ml.vanderschaar-lab.com/). 
* **[2023/11/15]** My solo paper [**Generative Semi-supervised Learning with Meta-Optimized Synthetic Samples**](https://arxiv.org/abs/2309.16143) has been received Best Paper Award from ACML 2023! 
* **[2023/09/22]** Our paper [**Regularizing Neural Networks with Meta-Learning Generative Models**](https://arxiv.org/abs/2307.13899) has been accepted to NeurIPS 2023! In this paper, we propose a novel meta-learning-based regularization method (MGR) using synthetic samples from pre-trained generative models. In contrast to conventional generative data augmentation methods, MGR utilizes the synthetic samples for regularizing only feature extractors and finds useful samples through meta learning of latent variables.
* **[2023/09/11]** My solo paper [**Generative Semi-supervised Learning with Meta-Optimized Synthetic Samples**](https://arxiv.org/abs/2309.16143) has been accepted to ACML 2023! This paper proposes a real unlabeled-dateless semi-supervised learning that utilizes a foundation generative models as the unlabeled data source. We introduce meta-optimization based sampling algorithm for extracting synthetic unlabeled data from the foundation generative model and cosine similarity based unsupervised loss function for updating the feature extractor of classifier by the synthetic samples.

---

# Activities
## Services as a Reviewer
- 2022: ICML, NeurIPS
- 2023: CVPR, PAKDD, ICML, ICCV, NeurIPS, IPSJ, DMLR@ICML2023, BMVC, ACML, TNNLS
- 2024: WACV, ICLR, CVPR, DMLR@ICLR2024, ICML, ECCV, NeurIPS, NeurIPS DB Track, ACML, DMLR@ICML2024, TMLR
- 2025: AAAI

---

# Biography
### Apr. 2022 - Current
Ph.D student at Dept. of Intelligence Science & Technology, Graduate School of Informatics, Kyoto University

### Apr. 2017 - Current
Researcher at NTT

### Apr. 2015 - Mar. 2017
M.E. from Dept. of Computer Engineering, Graduate School of Engineering, Yokohama National University

### Apr. 2011 - Mar. 2015
B.E. from Dept. of Computer Engineering, Yokohama National University

---

# Publications
- [Google Scholar](https://scholar.google.com/citations?user=_xJYVD0AAAAJ)
- [DBLP](https://dblp.org/pid/215/6588.html)

## International Conference
1. K. Adachi, S. Enomoto, T. Sasaki, <u>S. Yamaguchi</u>,  
[**Test-Time Similarity Modification for Person Re-Identification Toward Temporal Distribution Shift**](https://arxiv.org/abs/2403.14114),  
International Joint Conference on Neural Networks (IJCNN), 2024. 
2. S. Enomoto, N. Hasegawa, K. Adachi, T. Sasaki, <u>S. Yamaguchi</u>, S. Suzuki, T. Eda,  
[**Test-Time Adaptation Meets Image Enhancement: Improving Accuracy via Uncertainty-Aware Logit Switching**](https://arxiv.org/abs/2403.17423),  
International Joint Conference on Neural Networks (IJCNN), 2024. 
3. <u>S. Yamaguchi</u>, S. Kanai, K. Adachi, D. Chijiwa,  
[**Adaptive Random Feature Regularization on Fine-tuning Deep Neural Networks**](https://openaccess.thecvf.com/content/CVPR2024/html/Yamaguchi_Adaptive_Random_Feature_Regularization_on_Fine-tuning_Deep_Neural_Networks_CVPR_2024_paper.html),  
The IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2024. [[code]](https://github.com/yshinya6/adarand) [[arXiv]](https://arxiv.org/abs/2403.10097) 
4. <u>S. Yamaguchi</u>, S. Kanai, A. Kumagai, D. Chijiwa, H. Kashima,  
[**Regularizing Neural Networks with Meta-Learning Generative Models**](https://arxiv.org/abs/2307.13899),  
Neural Information Processing Systems (NeurIPS), 2023. 
5. <u>S. Yamaguchi</u>,  
[**Generative Semi-supervised Learning with Meta-Optimized Synthetic Samples**](https://proceedings.mlr.press/v222/yamaguchi24a.html),  
Asian Conference on Machine Learning (ACML), **Best Paper Award**, 2023. 
6. S. Suzuki, <u>S. Yamaguchi</u>, S. Takeda, S. Kanai, N. Makishima, A. Ando, R. Masumura,  
[**Adversarial Finetuning with Latent Representation Constraint to Mitigate Accuracy-Robustness Tradeoff**](https://arxiv.org/abs/2308.16454),  
The IEEE/CVF International Conference on Computer Vision (ICCV), 2023.
7. K. Adachi, <u>S. Yamaguchi</u>, A. Kumagai,  
[**Covariance-aware Feature Alignment with Pre-computed Source Statistics for Test-time Adaptation**](https://arxiv.org/abs/2204.13263),  
IEEE International Conference on Image Processing (ICIP), 2023.
8. S. Kanai, <u>S. Yamaguchi</u>, M. Yamada, H. Takahashi, Y. Ida,  
[**Switching One-Versus-the-Rest Loss to Increase the Margin of Logits for Adversarial Robustness**](https://arxiv.org/abs/2207.10283),  
International Conference on Machine Learning (ICML), 2023.
9. D. Chijiwa, <u>S. Yamaguchi</u>, A. Kumagai, Y. Ida,  
[**Meta-ticket: Finding optimal subnetworks for few-shot learning within randomly initialized neural networks**](https://arxiv.org/abs/2205.15619),  
Neural Information Processing Systems (NeurIPS), 2022.
10. K. Adachi, <u>S. Yamaguchi</u>,  
[**Learning Robust Convolutional Neural Networks with Relevant Feature Focusing via Explanations**](https://arxiv.org/abs/2202.04237),  
IEEE International Conference on Multimedia & Expo (ICME), 2022.
11. D. Chijiwa, <u>S. Yamaguchi</u>, Y. Ida, K. Umakoshi, T. Inoue,  
[**Pruning Randomly Initialized Neural Networks with Iterative Randomization**](https://openreview.net/pdf?id=QCPY2eMXYs),  
Neural Information Processing Systems (NeurIPS, **Spotlight**), 2021. [[arXiv]](https://arxiv.org/abs/2106.09269) [[code]](https://github.com/dchiji-ntt/iterand)
12. <u>S. Yamaguchi</u>, S. Kanai,  
[**F-Drop&Match: GANs with a Dead Zone in the High-Frequency Domain**](https://openaccess.thecvf.com/content/ICCV2021/html/Yamaguchi_F-DropMatch_GANs_With_a_Dead_Zone_in_the_High-Frequency_Domain_ICCV_2021_paper.html),  
International Conference on Computer Vision (ICCV), 2021. [[arXiv]](https://arxiv.org/abs/2106.02343)
13. <u>S. Yamaguchi</u>, S. Kanai, T. Shioda, S. Takeda,  
[**Image Enhanced Rotation Prediction for Self-Supervised Learning**](https://ieeexplore.ieee.org/document/9506132),  
IEEE International Conference on Image Processing (ICIP), 2021. [[arXiv]](https://arxiv.org/abs/1912.11603)
14. S. Kanai, M. Yamada, <u>S. Yamaguchi</u>, H. Takahashi, Y. Ida,   
[**Constraining Logits by Bounded Function for Adversarial Robustness**](https://ieeexplore.ieee.org/document/9533777),  
International Joint Conference on Neural Networks (IJCNN), 2021. [[arXiv]](https://arxiv.org/abs/2010.02558)
15. <u>S. Yamaguchi</u>, S. Kanai, T. Eda,  
[**Effective Data Augmentation with Multi-Domain Learning GANs**](https://ojs.aaai.org/index.php/AAAI/article/view/6131),  
AAAI Conference on Artificial Intelligence (AAAI), 2020. [[arXiv]](https://arxiv.org/abs/1912.11597)
16. <u>S. Yamaguchi</u>, K. Kuramitsu,  
[**A Fusion Techniques of Schema and Syntax Rules for Validating Open Data**](https://link.springer.com/chapter/10.1007/978-3-319-56660-3_37),  
Asian Conference on Intelligent Information and Database Systems (ACIIDS), 2017

## International Workshop (Refereed)
1. K. Adachi, <u>S. Yamaguchi</u>, Atsutoshi Kumagai  
[**Test-time Adaptation for Regression by Subspace Alignment**](https://tta-cvpr2024.github.io/_downloads/5c8596c2798bf34ada89ed342bb08d51/matc_1_test_time_adaptation_for_regre.pdf),  
The 1st Workshop on Test-Time Adaptation at CVPR 2024. **Special Mentioned.**
2. <u>S. Yamaguchi</u>,  
**Analyzing Diffusion Models on Synthesizing Training Datasets**,  
Data-centric Machine Learning Workshop at ICLR 2024. 
3. <u>S. Yamaguchi</u> and T. Fukuda,  
[**On the Limitation of Diffusion Models for Synthesizing Training Datasets**](https://arxiv.org/abs/2311.13090),  
SyntheticData4ML Workshop at NeurIPS 2023. 
4.  <u>S. Yamaguchi</u>, S. Kanai, A. Kumagai, D. Chijiwa, H. Kashima,  
[**Regularizing Neural Networks with Meta-Learning Generative Models**](https://arxiv.org/abs/2307.13899),  
Data-centric Machine Learning Research (DMLR) Workshop at ICML 2023. 

## Preprints
1. S. Kanai, Y. Ida, K. Adachim M. Uchida, T. Yoshida, <u>S. Yamaguchi</u>,  
[**Evaluating Time-Series Training Dataset through Lens of Spectrum in Deep State Space Models**](https://arxiv.org/abs/2408.16261),  
arXiv, 2024.
2. M. Yamada, T. Yamashita, <u>S. Yamaguchi</u>, D. Chijiwa,  
[**Revisiting Permutation Symmetry for Merging Models between Different Datasets**](https://arxiv.org/abs/2306.05641),  
arXiv, 2023.
3. <u>S. Yamaguchi</u>, S. Kanai, A. Kumagai, D. Chijiwa, H. Kashima,  
[**Transfer Learning with Pre-trained Conditional Generative Models**](https://arxiv.org/abs/2204.12833),  
arXiv, 2022.
4. <u>S. Yamaguchi</u>, S. Kanai, T. Shioda, S. Takeda,  
[**Multiple pretext-task for self-supervised learning via mixing multiple image transformations**](https://arxiv.org/abs/1912.11603v1),  
arXiv, 2019.
5. K. Kuramitsu, <u>S. Yamaguchi</u>,  
[**XML Schema Validation using Parsing Expression Grammars**](https://peerj.com/preprints/1503.pdf),  
PeerJ PrePrints, 2015

---

# Honors
- Outstanding Reviewer: ICML 2022
- 令和四年度 (2022) PRMU研究奨励賞 (outstanding research award at a Japanese domestic conference)
- ACML2023 Best Paper Award

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GLL931QDKD"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GLL931QDKD');
</script>
