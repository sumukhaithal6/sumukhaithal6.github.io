---
title: "Domain Shift in Capsule Networks "
collection: publications
permalink: /publications/domain_shift_capsule_networks
# date: 2020
authors : "Rajath S*, Sumukh Aithal K*, Natarajan Subramanyam" 
venue: '10th International Conference on Pattern Recognition Applications and Methods (ICPRAM 2021)'
paperurl: 'https://www.scitepress.org/Papers/2021/102520/102520.pdf'
---
## One Sentence Summary
In this paper, we analyze how well capsule networks adapt to new domains by experimenting with multiple routing algorithms and comparing it with CNNs.
## Abstract
Capsule Networks are an exciting deep learning architecture which overcomes some of the shortcomings of Convolutional Neural Networks (CNNs). Capsule networks aim to capture spatial relationships between parts of an object and exhibits viewpoint invariance. In practical computer vision, the training data distribution is different from the test distribution and the covariate shift affects the performance of the model. This problem is called Domain Shift. In this paper, we analyze how well capsule networks adapt to new domains by experimenting with multiple routing algorithms and comparing it with CNNs.
## Paper Summary
### Motivation
Our hypothesis is that capsule networks will have a smaller domain shift as compared to CNNs. The motivation behind this hypothesis is that since capsule networks claim to capture the spatial relationship between parts of an object, the network should be less susceptible to domain shift when compared to CNNs.
We analyse three different routing techniques namely Dynamic Routing, EM Routing and Self Routing and evaluate their effect on domain shift.
### Results
We evaluate the performance of three different source-target pairs. We train a model on source evaluate the performance on target. Both the source and target dataset contain the same classes but are from different distribution. The analysis is done using SVHN-MNIST, MNIST-MNISTM and CIFAR-10 to STL-10. \
We observe that EM-routing performs well amongst all routing techniques, and most of the time performing better than CNNs in terms of minimizing domain shift.
### Conclusion
In this paper, we have carried out a comprehensive analysis of Domain Shift in Capsule Networks by considering different routing algorithms. Using a Capsule network with different routing techniques, we examined how well these models adapt to new domains. Further work can be done to use Capsule networks for domain adaptation and domain generalization.

## \[[<span style="color:blue">Paper</span>](https://www.scitepress.org/Papers/2021/102520/102520.pdf)\]
