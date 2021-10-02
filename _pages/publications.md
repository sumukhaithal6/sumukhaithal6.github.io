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

[**S<sup>3</sup>VAADA: Submodular Subset Selection for Virtual Adversarial Active Domain Adaptation**](/publications/s3_vaada)<br/>
Harsh Rangwani, Arihant Jain*, **Sumukh K Aithal\***, R. Venkatesh Babu <br/>
In International Conference on Computer Vision (**ICCV**) 2021. [[Project Website]](https://sites.google.com/iisc.ac.in/s3vaada-iccv2021/)
<details>
  <summary>One Sentence Summary</summary>
  
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
**PMLR: NeurIPS 2020 Competition and Demonstration Track, 2020** [[Paper]](proceedings.mlr.press/v133/jiang21a/jiang21a.pdf)
<details>
  <summary>One Sentence Summary</summary>
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
  <summary>One Sentence Summary</summary>
  
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

  <summary>One Sentence Summary</summary>

  In this paper, we analyze how well capsule networks adapt to new domains by experimenting with multiple routing algorithms and comparing it with CNNs.

</details>
<!-- <br/> -->

<details>

  <summary>Abstract</summary>

 Capsule Networks are an exciting deep learning architecture which overcomes some of the shortcomings of Convolutional Neural Networks (CNNs). Capsule networks aim to capture spatial relationships between parts of an object and exhibits viewpoint invariance. In practical computer vision, the training data distribution is different from the test distribution and the covariate shift affects the performance of the model. This problem is called Domain Shift. In this paper, we analyze how well capsule networks adapt to new domains by experimenting with multiple routing algorithms and comparing it with CNNs.

</details>

