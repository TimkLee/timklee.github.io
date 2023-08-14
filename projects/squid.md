---
layout: page
title: Act as I Say - Learning to Pretend to be Something You’re Not
permalink: /projects/squid
---




<div class="parent">
<figure>
    <img src="/images/squid_supermorphology.png" alt="squid_supermorphology" class="postimg" style="width: 100%;" />
    <figcaption>Example of Supermorphology</figcaption>
</figure>
</div>

<b>Type:</b> IFT 6163 (Robot Learning) Project

<b>Year:</b> 2023

<b>Teammates:</b> Charlie Gauthier

<b>Key Skills:</b> Python; Deep Reinforcement Learning; Machine Learning Pipeline; Machine Learning Libraries

<b>Additional Information:</b> [Course Website](https://neo-x.github.io/teaching/ift6163.html)

<b>Objectives:</b>
- Develop a framework for training generalized policies for controlling a morphologically adaptable robot.

<b>Summary: </b>
<br> Adaptability in robotic systems is highly desirable. This project explores the method of training a generalized policy that is capable of selecting the best morphology given the goal condition. The approach borrows ideas from [GAIL](https://arxiv.org/abs/1606.03476) to provide extra training signals and from [WaveNet](https://arxiv.org/abs/1609.03499) to provide insights on the structure of the input data.

- PyTorch was used as the primary library for establishing the codebase.
- The [PPO](https://arxiv.org/abs/1707.06347) algorithm is used as the primary learning algorithm.
- Explored different simulation environments including OpenAI Gym, Mujoco, and Issac Gym.
- Developed custom models for simulation and physical experiments.





<div class="parent">
<figure>
    <img src="/images/squid_adaptiveness.png" alt="squid_adaptiveness" style="width: 100%;" />
    <figcaption>System Adaptiveness Progression</figcaption>
</figure>
</div>

<div class="parent">
<figure>
    <img src="/images/squid_train_algo.png" alt="squid_train_algo" style="width: 100%;" />
    <figcaption>Training the Adaptive Policy with an Offline Discriminator</figcaption>
</figure>
</div>