---
title: "AutoUnmix: an autoencoder-based spectral unmixing method for multi-color fluorescence microscopy imaging"
collection: publications
category: manuscripts
permalink: /publication/BOE-2023-Unmix
excerpt: 'Propose a deep learning-based blindly spectral unmixing method, termed AutoUnmix, to imitate the physical spectral mixing process. Our proposed method has demonstrated real-time unmixing capabilities, surpassing existing methods by up to 100-fold in terms of unmixing speed.'
date: 2023-09-01
venue: 'Biomedical Optics Express'
paperurl: 'https://hitsh95.github.io/shahao/files/boe-14-9-4814.pdf'
citation: 'Jiang, Y., Sha, H., Liu, S., Qin, P. & Zhang, Y. AutoUnmix: an autoencoder-based spectral unmixing method for multi-color fluorescence microscopy imaging. Biomedical Optics Express 14(2023).'
---

Multiplexed fluorescence microscopy imaging is widely used in biomedical applica- tions. However, simultaneous imaging of multiple fluorophores can result in spectral leaks and overlapping, which greatly degrades image quality and subsequent analysis. Existing popular spectral unmixing methods are mainly based on computational intensive linear models, and the performance is heavily dependent on the reference spectra, which may greatly preclude its further applications. In this paper, we propose a deep learning-based blindly spectral unmixing method, termed AutoUnmix, to imitate the physical spectral mixing process. A transfer learning framework is further devised to allow our AutoUnmix to adapt to a variety of imaging systems without retraining the network. Our proposed method has demonstrated real-time unmixing capabilities, surpassing existing methods by up to 100-fold in terms of unmixing speed. We further validate the reconstruction performance on both synthetic datasets and biological samples. The unmixing results of AutoUnmix achieve the highest SSIM of 0.99 in both three- and four-color imaging, with nearly up to 20% higher than other popular unmixing methods. For experiments where spectral profiles and morphology are akin to simulated data, our method realizes the quantitative performance demonstrated above. Due to the desirable property of data independency and superior blind unmixing performance, we believe AutoUnmix is a powerful tool for studying the interaction process of different organelles labeled by multiple fluorophores.
