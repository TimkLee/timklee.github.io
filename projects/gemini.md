---
layout: page
title: Generative Gemini - Utilizing Generational Gap for Exploration in Reinforcement Learning
permalink: /projects/gemini
---




<div class="parent">
<figure>
    <img src="/images/gemini_env.png" alt="gemini_env" class="postimg" style="width: 100%;" />
    <figcaption>MiniGrid Test Environment</figcaption>
</figure>
</div>

<b>Type:</b> COMP 579 (Reinforcement Learning) Project

<b>Year:</b> 2023

<b>Teammates:</b> Krishna Maneesha Dendukuri, Hena Ghonia

<b>Key Skills:</b> Python; Deep Reinforcement Learning; Machine Learning Pipeline; Machine Learning Libraries

<b>Additional Information:</b> [Course Website](https://www.cs.mcgill.ca/~dprecup/courses/rl.html)

<b>Objectives:</b>
- Develop a framework that promotes mindful and intentional exploration and is adaptable to different environment.

<b>Summary: </b>
<br> One of the greatest challenges in reinforcement learning is insufficient exploration, especially in dynamic and sparse reward environments. Borrowing ideas from contrastive learning and generative adversarial networks, the proposed approach uses two different generators to influence the decision of the policy network. The modified decisions would allow the agent to explore novel state spaces, ultimately leading to a better-performing policy. The preliminary results suggest that additional work is required.
- PyTorch was used as the primary library for establishing the codebase. 
- The Minigrid environment was selected as the test environment.
- The [DQN](https://arxiv.org/abs/1312.5602) model was implemented as the baseline algorithm.
- My primary focus was on developing the new algorithm.



<div class="parent">
<figure>
    <img src="/images/gemini_algorithm.png" alt="gemini_algorithm" class="postimg" style="width: 100%;" />
    <figcaption>Proposed Algorithm Structure</figcaption>
</figure>
</div>