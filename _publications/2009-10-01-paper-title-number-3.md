---
title: "Lossless compression of structured convolutional models via lifting"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-3
excerpt: 'We introduce a lossless compression technique to speed up models such as Graph Neural Networks'
date: 2021-05-17
venue: 'ICLR 2021'
paperurl: 'https://openreview.net/pdf?id=oxnp2q-PGL4'
---
Lifting is an efficient technique to scale up graphical models generalized to relational domains by exploiting the underlying symmetries. Concurrently, neural models are continuously expanding from grid-like tensor data into structured representations, such as various attributed graphs and relational databases. To address the irregular structure of the data, the models typically extrapolate on the idea of convolution, effectively introducing parameter sharing in their, dynamically unfolded, computation graphs. The computation graphs themselves then reflect the symmetries of the underlying data, similarly to the lifted graphical models. Inspired by lifting, we introduce a simple and efficient technique to detect the symmetries and compress the neural models without loss of any information. We demonstrate through experiments that such compression can lead to significant speedups of structured convolutional models, such as various Graph Neural Networks, across various tasks, such as molecule classification and knowledge-base completion.

citation: '@inproceedings{
           sourek2021lossless,
           title={Lossless Compression of Structured Convolutional Models via Lifting},
           author={Gustav Sourek and Filip Zelezny and Ondrej Kuzelka},
           booktitle={International Conference on Learning Representations},
           year={2021},
           url={https://openreview.net/forum?id=oxnp2q-PGL4}
           }'