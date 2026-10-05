---
title: "How I Met Your Bias: Investigating Bias Amplification in Diffusion Models"
collection: publications
category: conferences
permalink: /publication/2026-03-04-how-i-met-your-bias
excerpt: 'For the first time, we show that sampling hyperparameters influence bias amplification in diffusion models during the inference process, across sampling algorithms, datasets, and model architectures.'
date: 2026-03-04
venue: '2026 IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)'
authors: '**Nathan Roos**, Ani Gjergji, Ekaterina Iakovleva, Vito Paolo Pastore and Enzo Tartaglione'
---

Diffusion-based generative models demonstrate state-of-the-art performance across various image synthesis tasks, yet their tendency to replicate and amplify dataset biases remains poorly understood. Although previous research has viewed bias amplification as an inherent characteristic of diffusion models, this work provides the first analysis of how sampling algorithms and their hyperparameters influence bias amplification. We empirically demonstrate that samplers for diffusion models -- commonly optimized for sample quality and speed -- have a significant and measurable effect on bias amplification. Through controlled studies with models trained on Biased MNIST, Multi-Color MNIST and BFFHQ, and with Stable Diffusion, we show that sampling hyperparameters can induce both bias reduction and amplification, even when the trained model is fixed.

Links:
[paper](https://ieeexplore.ieee.org/document/11492321)
[source code](https://github.com/How-I-met-your-bias/how_i_met_your_bias),
[presentation video](https://www.youtube.com/watch?v=hbO--PTNufk),
[poster](https://wacv.thecvf.com/media/PosterPDFs/WACV%202026/230.png?t=1771442588.589064).

