---
layout: article
title: "Reading Text from Images"
categories: articles
excerpt: "Text in natural scene images contains rich semantic information that is crucial for visual understanding and reasoning. Although OCR has been studied extensively, reading irregular text of arbitrary shape is still a challenging task. Some of our work was published in ICCV and AAAI."
tags: [sample, images, test]
ads: false
image:
  teaser: research_text.png
video:
---
- We proposed an end-to-end trainable network for joint text detection and recognition. This is one of the first works that put text detection and recognition into a single framework. 

    <u>Related work:<u/>

    &radic; &nbsp; &nbsp; H. Li, P. Wang, C. Shen. **Towards End-to-end Text Spotting with Convolutional Recurrent Neural Networks**. In: ICCV, 2017.

    &radic; &nbsp; &nbsp; H. Li, P. Wang#, C. Shen. **Toward End-to-end Car License Plate Detection and Recognition with Deep Neural Networks**. In: TITS, 2018.

- We proposed two simple irregular text recognizers based on encoder-decoder frameworks and 2d-attention mechanisms. These two models serve as part of the model ensemble that won the 1st place in the Task2 (Text Line Recognition in the Signboard) of ICDAR 2019 Robust Reading Challenge on Reading Chinese Text on Signboard. <a href="https://rrc.cvc.uab.es/files/ICDAR2019-ReCTS.pdf">leaderboard</a>, <a href="https://github.com/wangpengnorman/SAR-Strong-Baseline-for-Text-Recognition">code</a>   

    <u>Related work:<u/>

	&radic; &nbsp; &nbsp; H. Li, P. Wang, C. Shen, G. Zhang. **Show, Attend and Read: A Simple and Strong Baseline for Irregular Text Recognition**. In: AAAI, 2019.

    &radic; &nbsp; &nbsp; P. Wang, L. Yang, H. Li, Y. Deng, C. Shen, Y. Zhang. **A Simple and Robust Convolutional-Attention Network for Irregular Text Recognition**. In: arXiv:1904.01375, 2019

