---
title: "Evaluation of CNN-based automatic music tagging models"
layout: post
date: 2020-06-26 12:00
tag: projects
image: /assets/images/posts/smc2020_music_autotagging.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
category: project
author: dbogdanov
externalLink: false
---



Our new paper for [SMC 2020](https://smc2020torino.it/) led by [Minz Won](https://minzwon.github.io/
) compares different state-of-the-art CNN music auto-tagging models in a reference evaluation on three datasets, and the great thing is all the models are available in PyTorch! 

[https://github.com/minzwon/sota-music-tagging-models](https://github.com/minzwon/sota-music-tagging-models)

![CNN Models Evaluation]({{ site.url }}/assets/images/posts/smc2020_music_autotagging.png)

[Evaluation of CNN-based automatic music tagging models](https://smc2020torino.it/adminupload/file/SMCCIM_2020_paper_210.pdf).
Won, M., Ferraro A., Bogdanov D., & Serra X.
In 17th Sound and Music Computing Conference (SMC2020), 2020.

> Recent advances in deep learning accelerated the development of content-based automatic music tagging systems. Music information retrieval (MIR) researchers proposed various architecture designs, mainly based on convolutional neural networks (CNNs), that achieve state-of-the-art results in this multi-label binary classification task. However, due to the differences in experimental setups followed by researchers, such as using different dataset splits and soft-ware versions for evaluation, it is difficult to compare the proposed architectures directly with each other. To facilitate further research, in this paper we conduct a consistent evaluation of different music tagging models on three datasets (MagnaTagATune, Million Song Dataset, and MTG-Jamendo) and provide reference results using common evaluation metrics (ROC-AUC and PR-AUC). Furthermore, all the models are evaluated with perturbed inputs to investigate the generalization capabilities concerning time stretch, pitch shift, dynamic range compression, and addition of white noise. For reproducibility, we provide the PyTorchimplementations with the pre-trained models.
