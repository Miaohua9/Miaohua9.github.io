---
title: "Ssfe-net: Self-supervised feature enhancement for ultra-fine-grained few-shot class incremental learning"
collection: publications
category: conferences
permalink: /publication/2023-01-07-paper-title-number-8
excerpt: 'A self-supervised learning (SSL) and knowledge distillation (KD) framework is developed to enhance the feature extraction of the low-capacity backbone network for ultra-FGVC few-shot class incremental learning tasks. '
date: 2023-01-07
venue: 'WACV2023'
paperurl: 'https://ieeexplore.ieee.org/document/10030400'
citation: 'Pan, Z., Yu, X., Zhang, M., & Gao, Y. (2023). Ssfe-net: Self-supervised feature enhancement for ultra-fine-grained few-shot class incremental learning. In Proceedings of the IEEE/CVF winter conference on applications of computer vision (pp. 6275-6284).'
---

Ultra-Fine-Grained Visual Categorization (ultra-FGVC) has become a popular problem due to its great real-world potential for classifying the same or closely related species with very similar layouts. However, there present many challenges for the existing ultra-FGVC methods, firstly there are always not enough samples in the existing ultra-FGVC datasets based on which the models can easily get overfitting. Secondly, in practice, we are likely to find new species that we have not seen before and need to add them to existing models, which is known as incremental learning. The existing methods solve these problems by Few-Shot Class Incremental Learning (FSCIL), but the main challenge of the FSCIL models on ultra-FGVC tasks lies in their inferior discrimination detection ability since they usually use low-capacity networks to extract features, which leads to insufficient discriminative details extraction from ultra-fine-grained images. In this paper, a self-supervised feature enhancement for the few-shot incremental learning network (SSFE-Net) is proposed to solve this problem. Specifically, a self-supervised learning (SSL) and knowledge distillation (KD) framework is developed to enhance the feature extraction of the low-capacity backbone network for ultra-FGVC few-shot class incremental learning tasks. Besides, we for the first time create a series of benchmarks for FSCIL tasks on two public ultra-FGVC datasets and three normal fine-grained datasets, which will facilitate the development of the Ultra-FGVC community. Extensive experimental results on public ultra-FGVC datasets and other state-of-the-art benchmarks consistently demonstrate the effectiveness of the proposed method.
