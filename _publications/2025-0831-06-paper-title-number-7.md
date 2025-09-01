---
title: "DyCR: A dynamic clustering and recovering network for few-shot class-incremental learning"
collection: publications
category: journal
permalink: /publication/2025-05-16-paper-title-number-4\7
excerpt: 'a novel orthogonal decomposition mechanism is developed to split the feature embeddings into context and category information.'
date: 2024-05-16
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
paperurl: 'https://ieeexplore.ieee.org/document/10531293'
citation: 'Pan, Z., Yu, X., Zhang, M., Zhang, W., & Gao, Y. (2024). DyCR: A dynamic clustering and recovering network for few-shot class-incremental learning. IEEE transactions on neural networks and learning systems, 36(4), 7116-7129.'
---

Few-shot class-incremental learning (FSCIL) aims to continually learn novel data with limited samples. One of the major challenges is the catastrophic forgetting problem of old knowledge while training the model on new data. To alleviate this problem, recent state-of-the-art methods adopt a well-trained static network with fixed parameters at incremental learning stages to maintain old knowledge. These methods suffer from the poor adaptation of the old model with new knowledge. In this work, a dynamic clustering and recovering network (DyCR) is proposed to tackle the adaptation problem and effectively mitigate the forgetting phenomena on FSCIL tasks. Unlike static FSCIL methods, the proposed DyCR network is dynamic and trainable during the incremental learning stages, which makes the network capable of learning new features and better adapting to novel data. To address the forgetting problem and improve the model performance, a novel orthogonal decomposition mechanism is developed to split the feature embeddings into context and category information. The context part is preserved and utilized to recover old class features in future incremental learning stages, which can mitigate the forgetting problem with a much smaller size of data than saving the raw exemplars. The category part is used to optimize the feature embedding space by moving different classes of samples far apart and squeezing the sample distances within the same classes during the training stage. Experiments show that the DyCR network outperforms existing methods on four benchmark datasets.
