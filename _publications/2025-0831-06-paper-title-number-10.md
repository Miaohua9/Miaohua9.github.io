---
title: "Joint image denoising with gradient direction and edge-preserving regularization"
collection: publications
category: manuscripts
permalink: /publication/2022-05-17-paper-title-number-10
excerpt: 'A new gradient-direction-based method is proposed to avoid the denoised edges to be blurred especially when the edges of the guidance image are weak or inexistent.'
date: 2022-05-17
venue: 'Pattern Recognition'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0031320321006828'
citation: 'Li, P., Liang, J., Zhang, M., Fan, W., & Yu, G. (2022). Joint image denoising with gradient direction and edge-preserving regularization. Pattern Recognition, 125, 108506.'
---

Joint image denoising algorithms use the structures of the guidance image as a prior to restore the noisy target image. While the provided guidance images are helpful to improve the denoising performance, the denoised edges are most likely to be blurred especially when the edges of the guidance image are weak or inexistent. To address this weakness, this paper proposes a new gradient-direction-based joint image denoising method in which the absolute cosine value of the angle between two gradient vectors of the guidance image and those of the image to recover is employed as the parallel measurement to ensure that the gradient directions of the denoised image are approximately the same as or opposite to those of the guidance image. Besides, a new edge-preserving regularization term is developed to alleviate the effects of the unreliable prior information from guidance image. To simplify the resultant complex nonconvex and nonlinear fractional model, the logarithm function is employed to convert the multiplication operation into addition operation. Then, we construct the surrogate function for the logarithmic term of l 2-norm, and separate the variables to transform the objective function into convex one with high numerical stability while retaining high efficiency. Finally, the optimal solutions can be obtained by directly minimizing the convex functions. Experimental results on public datasets and from nine benchmark methods consistently demonstrate the effectiveness of the proposed method both visually and quantitatively.
