---
title: "Efficient Atmospheric Correction for Onboard Processing Using Knowledge Distillation and Model Compression"
collection: publications
category: conferences
permalink: /publication/Efficient Atmospheric Correction for Onboard Processing Using Knowledge Distillation and Model Compression
excerpt: 'This paper introduces an innovative deep learning-based solution for atmospheric correction in remote sensing, specifically designed for resource-constrained spaceborne systems.'
date: 2024-11-27
venue: '2024 International Conference on Digital Image Computing: Techniques and Applications (DICTA)'
paperurl: 'https://ieeexplore.ieee.org/document/10869604'
citation: 'Zhang, M., Cheraghian, A., Qin, Y., Benn, D., Rollan, T., & Habili, N. (2024, November). Efficient Atmospheric Correction for Onboard Processing Using Knowledge Distillation and Model Compression. In 2024 International Conference on Digital Image Computing: Techniques and Applications (DICTA) (pp. 632-639). IEEE.'
---

This paper introduces an innovative deep learning-based solution for atmospheric correction in remote sensing, specifically designed for resource-constrained spaceborne systems. We train the UNet deep learning model with 3D kernels on a synthetic dataset derived from Hyperion imagery over Australia and then utilize knowledge distillation to develop a lightweight model that maintains accuracy while minimizing computational demands. The lightweight model undergoes static quantization and is then deployed on the Raspberry Pi 4 platform. The Raspberry Pi 4 is known for its computational efficiency and aligns with spaceborne computational constraints, offering a practical solution for onboard processing. Major contributions include utilizing available remote sensing data and a physics-based method to create an extensive synthetic dataset resembling typical atmospheric conditions and geographic terrains, as well as outlining an AI processing workflow encompassing synthetic dataset generation, optimal model training, knowledge distillation for lightweight model training, and model compression through static quantization for resource-constrained environments. The results demonstrate the successful deployment of atmospheric correction on the Raspberry Pi 4.
