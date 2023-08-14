---
layout: page
title: Analysis of Image Augmentation Methods on Different Types of Learning Problems
permalink: /projects/ml_augmentation
---




<div class="parent">
<figure>
    <img src="/images/ml_aug_mix.png" alt="ml_aug_mix" class="postimg" style="width: 70%;" />
    <figcaption>Example of Cutmix Augmentation</figcaption>
</figure>
</div>

<b>Type:</b> IFT 6759 (Advanced Projects in Machine Learning) Project

<b>Year:</b> 2022

<b>Teammates:</b> Krishna Maneesha Dendukuri, Rakshit Shetty, Yassir Mamouni, Alekhya Dronavalli, Prishruit Punia

<b>Key Skills:</b> Python; Deep Learning; Machine Learning Pipeline; Machine Learning Libraries

<b>Additional Information:</b> [Project Repository](https://github.com/TimkLee/IFT6759), [Project Presentation](https://alexhernandezgarcia.github.io/assets/pdf/mlprojects22/imageaugmentation.pdf)

<b>Objectives:</b>
- Explore and compare the effectiveness of individual data augmentation techniques and their combinations in Supervised and Semi-Supervised Settings.
- Establish a machine learning pipeline suitable for a large number of experiments.

<b>Summary: </b>
<br> Image classification is a classic machine learning task and remains an ongoing research topic. Various augmentation methods were developed to improve model performance. We wanted to verify the benefits of different augmentation techniques and observe their effect on model performance and interpretability. The team consists of six members for tackling the large number of experiments that need to be run given the time constraint.
- PyTorch was used as the primary library for establishing the codebase.
- Experiments were performed on the CIFAR-10 dataset.
- Implemented the ResNet-20 and the All-CNN network architectures.
- Implemented augmentation techniques Cutout, Cutmix, and Mixup.
- Established a modulus machine learning pipeline that executes and records the experiment following the user-defined configuration file.



<div class="parent">
<figure>
    <img src="/images/ml_aug_compare.png" alt="ml_aug_compare" class="postimg" style="width: 100%;" />
    <figcaption>Comparison of the Best Performing Augmentations</figcaption>
</figure>
</div>