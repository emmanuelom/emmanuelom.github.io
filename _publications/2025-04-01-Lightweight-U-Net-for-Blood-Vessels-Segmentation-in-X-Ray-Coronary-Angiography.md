---
title: "Lightweight U-Net for Blood Vessels Segmentation in X-Ray Coronary Angiography"
collection: publications
category: manuscripts
permalink: /publication/2025-04-01-Lightweight-U-Net-for-Blood-Vessels-Segmentation-in-X-Ray-Coronary-Angiography
date: 2025-04-01
venue: "Journal of Imaging"
citation: "Ramos-Cortez, J. S., Alvarado-Carrillo, D. E., Ovalle-Magallanes, E., & Avina-Cervantes, J. G. (2025). Lightweight U-Net for Blood Vessels Segmentation in X-Ray Coronary Angiography. Journal of Imaging, 11(4), 106. https://doi.org/10.3390/jimaging11040106"
paperurl: "https://doi.org/10.3390/jimaging11040106"
tags: ['journal', 'segmentation', 'XCA']
---

## Abstract

Blood vessel segmentation in X-ray coronary angiography (XCA) plays a crucial role in diagnosing cardiovascular diseases, enabling a precise assessment of arterial structures. However, segmentation is challenging due to a low signal-to-noise ratio, interfering background structures, and vessel bifurcations, which hinder the accuracy of deep learning models. Additionally, deep learning models for this task often require high computational resources, limiting their practical application in real-time clinical settings. This study proposes a lightweight variant of the U-Net architecture using a structured kernel pruning strategy inspired by the Lottery Ticket Hypothesis. The pruning method systematically removes entire convolutional filters from each layer based on a global reduction factor, generating compact subnetworks that retain key representational capacity. This results in a significantly smaller model without compromising the segmentation performance. This approach is evaluated on two benchmark datasets, demonstrating consistent improvements in segmentation accuracy compared to the vanilla U-Net. Additionally, model complexity is significantly reduced from 31 M to 1.9 M parameters, improving efficiency while maintaining high segmentation quality.