---
title: "Lifted Relational Neural Networks: Efficient Learning of Latent Relational Structures"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This paper introduces our original concept of Lifted Relational Neural Networks (from 2015)'
date: 2018-05-17
venue: 'Journal of Artificial Intelligence Research'
paperurl: 'https://jair.org/index.php/jair/article/view/11203/26415'

---
**G Sourek, V Aschenbrenner, F Zelezny, O Kuzelka**

We propose a method to combine the interpretability and expressive power of first-order logic with the effectiveness of neural network learning. In particular, we introduce a lifted framework in which first-order rules are used to describe the structure of a given problem setting. These rules are then used as a template for constructing a number of neural networks, one for each training and testing example. As the different networks corresponding to different examples share their weights, these weights can be efficiently learned using stochastic gradient descent. Our framework provides a flexible way for implementing and combining a wide variety of modelling constructs. In particular, the use of first-order logic allows for a declarative specification of latent relational structures, which can then be efficiently discovered in a given data set using neural network learning. Experiments on 78 relational learning benchmarks clearly demonstrate the effectiveness of the framework.

```
@article{sourek2018lifted,
         title={Lifted relational neural networks: Efficient learning of latent relational structures},
         author={Sourek, Gustav and Aschenbrenner, Vojtech and Zelezny, Filip and Schockaert, Steven and Kuzelka, Ondrej},
         journal={Journal of Artificial Intelligence Research},
         volume={62},
         pages={69--100},
         year={2018}
}
```