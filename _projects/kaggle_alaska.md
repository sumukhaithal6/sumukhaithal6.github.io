---
title: "Kaggle’s ALASKA2 Image Steganalysis"
excerpt: "Developed a Custom EfficientNet model to detect secret data hidden within images. 
<b>Won a Silver medal for being the Top 3% of all teams. Ranked 32/1095 teams</b> <br/>
<a href="https://www.kaggle.com/c/alaska2-image-steganalysis/overview">Competition Website</a>"
collection: projects
---
## One Sentence Summary
Developed a Custom EfficientNet B7 model to detect secret data hidden within images. 
## [About the Competition](https://www.kaggle.com/c/alaska2-image-steganalysis)
The goal of the competition was to develop an efficient and reliable method to detect secret data hidden within innocuous-seeming digital images.
Law enforcement officers need better methods to combat criminals using hidden messages. The data science community and other researchers can help with better automated detection. More accurate methods could help catch criminals whose communications are hidden in plain sight.
## Solution
For a given image, the model should predict the score that indicates how likely this image contains hidden data. the higher the score, the more it is assumed that image contains secret data.\
The dataset consisted of large number of images, both unaltered and altered with one of three different steganography algorithms (JMiPOD, JUNIWARD, UERD). \
We developed a EfficientNet B7 model to classify the image as one of 4 classes (Unaltered or Cover,JMiPOD, JUNIWARD, UERD). We used label smoothing and finetuned the optimizer and scheduler to get the best performance. For our final submission, we ensembled different models trained on different train-validation splits. We also experimented with different augmentations. \
The metric used for the competition was Weighted-AUC. (Higher is better)\
**Public Leaderboard** Score: 0.944 and Rank: 5/1095 \
**Private Leaderboard** Score: 0.924 and Rank: 32/1095 

### **Won a Silver medal for being the Top 3% of all teams. Ranked 32/1095 teams**
<a href="https://www.kaggle.com/c/alaska2-image-steganalysis/overview">Competition Website</a>