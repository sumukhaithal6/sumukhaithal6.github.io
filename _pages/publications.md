---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
urlcolor: blue
---
<style type="text/css">
    a {text-decoration:none;}
</style>
<br/>

**Escaping Saddle Points for Effective Generalization on Class-Imbalanced Data**<br/>
Harsh Rangwani\*, **Sumukh K Aithal\***, Mayank Mishra, R. Venkatesh Babu <br/>
In Neural Information Processing Systems (**NeurIPS**) 2022. [[Paper]](https://openreview.net/pdf?id=9DYKrsFSU2) [[Code-Coming Soon]](https://github.com/val-iisc/Saddle-LongTail) [[Slides]](https://sumukhaithal6.github.io/files/SaddleLongTail-NeurIPS22-Slides.pdf) [[Poster]](https://sumukhaithal6.github.io/files/SaddleLongTail-NeurIPS22-Poster.pdf)
<details>
  <summary>TLDR</summary>
 Tail class loss landscape converges to a saddle point in imbalanced datasets and SAM can effectively escape from these solutions.
 
</details>
<!-- <br/> -->
<details>
  <summary>Abstract</summary>
Real-world datasets exhibit imbalances of varying types and degrees. Several techniques based on re-weighting and margin adjustment of loss are often used to enhance the performance of neural networks, particularly on minority classes. In this work, we analyze the class-imbalanced learning problem by examining the loss landscape of neural networks trained with re-weighting and margin based techniques. Specifically, we examine the spectral density of Hessian of class-wise loss, through which we observe that the network weights converges to a saddle point in the loss landscapes of minority classes. Following this observation, we also find that optimization methods designed to escape from saddle points can be effectively used to improve generalization on minority classes. We further theoretically and empirically demonstrate that Sharpness-Aware Minimization (SAM), a recent technique that encourages convergence to a flat minima, can be effectively used to escape saddle points for minority classes. Using SAM results in a 6.2% increase in accuracy on the minority classes over the state-of-the-art Vector Scaling Loss, leading to an overall average increase of 4% across imbalanced datasets. The code is available at https://github.com/val-iisc/Saddle-LongTail.</details>

<!-- <br/> -->
<!-- <br/> -->
**A Closer Look at Smoothness at Domain Adversarial Training**<br/>
Harsh Rangwani\*, **Sumukh K Aithal\***, Mayank Mishra,  Arihant Jain, R. Venkatesh Babu <br/>
In International Conference on Machine Learning (**ICML**) 2022. [[Paper]](https://arxiv.org/abs/2206.08213) [[Code]](https://github.com/val-iisc/SDAT) [[Slides]](https://sumukhaithal6.github.io/files/SDAT-ICML-2022-Slides.pdf) [[Poster]](https://sumukhaithal6.github.io/files/SDAT-ICML-2022-Poster.pdf)
<details>
  <summary>TLDR</summary>
 Smooth Minima with respect to task loss leads to effective generalization on the target domain. 
 
</details>
<!-- <br/> -->
<details>
  <summary>Abstract</summary>
Domain adversarial training has been ubiquitous for achieving invariant representations and is used widely for various domain adaptation tasks. In recent times, methods converging to smooth optima have shown improved generalization for supervised learning tasks like classification. In this work, we analyze the effect of smoothness enhancing formulations on domain adversarial training, the objective of which is a combination of task loss (eg. classification, regression etc.) and adversarial terms. We find that converging to a smooth minima with respect to (w.r.t.) task loss stabilizes the adversarial training leading to better performance on target domain. In contrast to task loss, our analysis shows that converging to smooth minima w.r.t. adversarial loss leads to sub-optimal generalization on the target domain. Based on the analysis, we introduce the Smooth Domain Adversarial Training (SDAT) procedure, which effectively enhances the performance of existing domain adversarial methods for both classification and object detection tasks. Our analysis also provides insight into the extensive usage of SGD over Adam in the community for domain adversarial training. 
</details>
<!-- <br/> -->
<!-- <br/> -->

[**S<sup>3</sup>VAADA: Submodular Subset Selection for Virtual Adversarial Active Domain Adaptation**](/publications/s3_vaada)<br/>
Harsh Rangwani, Arihant Jain*, **Sumukh K Aithal\***, R. Venkatesh Babu <br/>
In International Conference on Computer Vision (**ICCV**) 2021. [[Project Website]](https://sites.google.com/iisc.ac.in/s3vaada-iccv2021/)
<details>
  <summary>TLDR</summary>
  
  Informative sample selection and effective adaptation through S<sup>3</sup>VAADA can lead to effective gains by using small amount of labeled target data.   

</details>
<!-- <br/> -->
<details>
  <summary>Abstract</summary>

Unsupervised domain adaptation (DA) methods have focused on achieving maximal performance through aligning features from source and target domains without using labeled data in the target domain. Whereas, in the real-world scenario’s it might be feasible to get labels for a small proportion of target data. In these scenarios, it is important to select maximally-informative samples to label and find an effective way to combine them with the existing knowledge from source data. Towards achieving this, we propose S3VAADA which i) introduces a novel submodular criterion to select a maximally informative subset to label and ii) enhances a cluster-based DA procedure through novel improvements to effectively utilize all the available data for improving generalization on target. Our approach consistently outperforms the competing state-of-the-art approaches on datasets with varying degrees of domain shifts. 
</details>
<!-- <br/> -->
<!-- <br/> -->

[**Methods and Analysis of The First Competition in Predicting Generalization of Deep Learning**](/publications/pgdl)<br/>
Yiding Jiang, Parth Natekar, Manik Sharma, **Sumukh K Aithal**, Dhruva Kashyap, Natarajan Subramanyam, Carlos Lassance, Daniel M. Roy, Gintare Karolina Dziugaite, Suriya Gunasekar, Isabelle Guyon, Pierre Foret, Scott Yak, Hossein Mobahi, Behnam Neyshabur, Samy Bengio <br/>
**PMLR: NeurIPS 2020 Competition and Demonstration Track, 2020** [[Paper]](https://proceedings.mlr.press/v133/jiang21a/jiang21a.pdf)
<details>
  <summary>TLDR</summary>
    A summary of the solutions of the top-three teams in the PGDL Competition.
</details>
<!-- <br/> -->
<details>
  <summary>Abstract</summary>

  Deep learning has been recently successfully applied to an ever larger number of problems, ranging from pattern recognition to complex decision making. However, several concerns have been raised, including guarantees of good generalization, which is of foremost importance. Despite numerous attempts, conventional statistical learning approaches fall short of providing a satisfactory explanation on why deep learning works. In a competition hosted at the Thirty-Fourth Conference on Neural Information Processing Systems (NeurIPS 2020), we invited the community to design robust and general complexity measures that can accurately predict the generalization of models. In this paper, we describe the competition design, the protocols, and the solutions of the top-three teams at the competition in details. In addition, we discuss the outcomes, common failure modes, and potential future directions for the competition.
</details>

[**Robustness to Augmentations as a Generalization Metric**](/publications/robustness_to_augmentations_as_a_generalization_metric)<br/>
**Sumukh Aithal K**\*, Dhruva Kashyap *, Natarajan Subramanyam <br/>
1st Runner Up in Predicting Generalization in Deep Learning, **NeurIPS 2020 Competition Track** 
\[[<span style="color:blue">Paper</span>](https://arxiv.org/abs/2101.06459)\] \[[<span style="color:blue">Video</span>](https://slideslive.com/38942495/robustness-to-augmentations-as-a-generalization-metric)\] 
\[[<span style="color:blue">Code</span>](https://github.com/sumukhaithal6/pgdl)\]
<details>
  <summary>TLDR</summary>
  
  In this work, we developed a simple yet effective method to predict the generalization performance of a model by using the concept that models that are robust to augmentations are more generalizable than those which are not.

</details>
<!-- <br/> -->
<details>
  <summary>Abstract</summary>

  Generalization is the ability of a model to predict on unseen domains and is a fundamental task in machine learning. Several generalization bounds, both theoretical and empirical have been proposed but they do not provide tight bounds. In this work, we propose a simple yet effective method to predict the generalization performance of a model by using the concept that models that are robust to augmentations are more generalizable than those which are not. We experiment with several augmentations and composition of augmentations to check the generalization capacity of a model. We also provide a detailed motivation behind the proposed method. The proposed generalization metric is calculated based on the change in the model’s output after augmenting the input. The proposed method was the first runner up solution for the competition "Predicting Generalization in Deep Learning".
</details>

<!-- <br/> -->
<!-- <br/> -->

**[Domain Shift in Capsule Networks](/publications/domain_shift_capsule_networks)**<br/>
Rajath S\*, **Sumukh Aithal K**\*, Natarajan Subramanyam <br/>
10th International Conference on Pattern Recognition Applications and Methods (**ICPRAM 2021**)
\[[<span style="color:blue">Paper</span>](https://www.scitepress.org/Papers/2021/102520/102520.pdf)\]

<details>

  <summary>TLDR</summary>

  In this paper, we analyze how well capsule networks adapt to new domains by experimenting with multiple routing algorithms and comparing it with CNNs.

</details>
<!-- <br/> -->

<details>

  <summary>Abstract</summary>

 Capsule Networks are an exciting deep learning architecture which overcomes some of the shortcomings of Convolutional Neural Networks (CNNs). Capsule networks aim to capture spatial relationships between parts of an object and exhibits viewpoint invariance. In practical computer vision, the training data distribution is different from the test distribution and the covariate shift affects the performance of the model. This problem is called Domain Shift. In this paper, we analyze how well capsule networks adapt to new domains by experimenting with multiple routing algorithms and comparing it with CNNs.

</details>

