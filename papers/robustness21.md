---
title: 'On Robustness and Transferability of Convolutional Neural Networks'
collection: publications
permalink: /publications/robustness21
date: 2020-07-16
authors: "Josip Djolonga, Jessica Yung, Michael Tschannen, Rob Romijnders, Lucas Beyer, Alexander Kolesnikov, Joan Puigcerver, Matthias Minderer, Alexander D'Amour, Dan Moldovan, Sylvain Gelly, Neil Houlsby, Xiaohua Zhai, Mario Lucic"
venue: 'Computer Vision and Pattern Recognition (CVPR), 2021'
# paperurl: 'https://openaccess.thecvf.com/content/CVPR2021/html/Djolonga_On_Robustness_and_Transferability_of_Convolutional_Neural_Networks_CVPR_2021_paper.html'
paperurl: 'https://arxiv.org/abs/2007.08558'
---

Modern deep convolutional networks (CNNs) are often criticized for not generalizing under distributional shifts. However, several recent breakthroughs in transfer learning suggest that these networks can cope with severe distribution shifts and successfully adapt to new tasks from a few training examples. In this work we study the interplay between out-of-distribution and transfer performance of modern image classification CNNs for the first time and investigate the impact of the pre-training data size, the model scale, and the data preprocessing pipeline. We find that increasing both the training set and model sizes significantly improve the distributional shift robustness. Furthermore, we show that, perhaps surprisingly, simple changes in the preprocessing such as modifying the image resolution can significantly mitigate robustness issues in some cases. Finally, we outline the shortcomings of existing robustness evaluation datasets and introduce a synthetic dataset SI-Score we use for a systematic analysis across factors of variation common in visual data such as object scale and position.
