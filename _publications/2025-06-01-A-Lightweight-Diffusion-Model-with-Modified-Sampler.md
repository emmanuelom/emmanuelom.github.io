---
title: "A Lightweight Diffusion Model with Modified Sampler"
collection: publications
category: conferences
permalink: /publication/2025-06-01-A-Lightweight-Diffusion-Model-with-Modified-Sampler
date: 2025-06-01
venue: "Mexican Conference on Pattern Recognition"
citation: "Grynberg Portnoy, M., Ovalle-Magallanes, E. (2025). A Lightweight Diffusion Model with Modified Sampler. In: López-Monroy, A.P., Rosales-Pérez, A., Carrasco-Ochoa, J.A., Martínez-Trinidad, J.F., Olvera-López, J.A. (eds) Pattern Recognition. MCPR 2025. Lecture Notes in Computer Science, vol 15715. Springer, Cham. https://doi.org/10.1007/978-3-031-96255-4_35"
paperurl: "https://doi.org/10.1007/978-3-031-96255-4_35"
tags: ['conference', 'diffusion-model', 'generative']
---

## Abstract

Generative models hold great potential in various applications, such as anomaly detection, image-to-image translation, super-res-olution, and denoising. However, their complexity can make implementation and reproducibility challenging, hindering progress, creating barriers to adoption, and discouraging comparisons with existing methods. In this work, we propose a lightweight diffusion architecture with a simplified sampling procedure. We input the noise multiplier directly into the model rather than the timestep t. This design aims to balance computational cost and performance. We investigate how various parameters and architectural blocks impact generation quality, specifically measured using the Fréchet Inception Distance (FID). The proposed architecture is evaluated on two distinct tasks: face generation and super-resolution using the CelebA dataset. Our results demonstrate that the architecture achieves promising performance across these tasks, making it a viable option for scenarios requiring a compact model. We provide the related architecture and training code at https://github.com/mgp123/diffusion-learning.