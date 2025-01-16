---
layout: post
title: Introducing SophiaAlignment
---
Previous alignment methods typically divide a model's response into individual tokens or multiple reasoning steps using a predefined token, such as "\n". However, these approaches have a significant weakness: they fail to capture the actual decision points in the LLM training and inference process. To address this, we propose a series of model-self-defined (soft) step alignment methods. Specifically, we divide a reasoning response into multiple soft steps based on "model confidence". Furthermore, we design a series of alignment strategies, which include a progress reward model, an inference strategy, and reinforcement learning, based on this division method. These approaches aim to better identify potential alignment boundaries and improve the overall performance and consistency of the model.

