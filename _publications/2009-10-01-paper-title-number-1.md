---
title: "ConMamba: Contrastive Vision Mamba for Plant Disease Detection"
collection: publications
category: manuscripts
permalink: /publication/conmamba-contrastive-vision-mamba
excerpt: 'This paper proposes a contrastive learning framework using Vision Mamba for robust plant disease detection.'
date: 2025-06-03
venue: 'Under review'
paperurl: 'https://arxiv.org/pdf/2506.03213'

citation: 'Mamun, A. A., Zhang, M., Ahmedt-Aristizabal, D., Hayder, Z., & Awrangjeb, M. (2025). ConMamba: Contrastive Vision Mamba for Plant Disease Detection. arXiv preprint arXiv:2506.03213'
---
Plant Disease Detection (PDD) is a key aspect of precision agriculture. However, existing deep learning methods often rely on extensively annotated datasets, which are time-consuming and costly to generate. Self-supervised Learning (SSL) offers a promising alternative by exploiting the abundance of unlabeled data. However, most existing SSL approaches suffer from high computational costs due to convolutional neural networks or transformer-based architectures. Additionally, they struggle to capture long-range dependencies in visual representation and rely on static loss functions that fail to align local and global features effectively. To address these challenges, we propose ConMamba, a novel SSL framework specially designed for PDD. ConMamba integrates the Vision Mamba
Encoder (VME), which employs a bidirectional State Space Model (SSM) to capture long-range dependencies efficiently. Furthermore, we introduce a dual-level contrastive loss with dynamic weight adjustment to optimize local-global feature alignment. Experimental results on three benchmark datasets demonstrate that ConMamba significantly outperforms state-of-the-art methods across multiple evaluation metrics. This provides an efficient and robust solution for PDD.
