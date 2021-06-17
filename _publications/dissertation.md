---
title: "*Deep Learning with Relational Logic Representations*"
collection: publications
permalink: /publication/dissertation
excerpt: 'This is actually my dissertation thesis - it contains my work on deep relational learning.'
date: 2021-05-11
venue: 'Czech Technical University press (theses)'
paperurl: 'https://gustiks.github.io/files/dissertation.pdf'
---

**Gustav Šír**

In the recent years, we have seen tremendous resurgence of neural networks, applied with great success in highly diverse domains, ranging from speech recognition to game playing. The unprecedented progress of this new deep learning trend has even been seen as paving our way towards general artificial intelligence.
However, the current deep learning models are still limited in many regards.
Particularly, in this thesis we address the contemporary problem of learning neural networks from *relational* data and knowledge representations. While virtually all standard models are limited to data in the form of fixed-size tensors, the relational data are omnipresent in the interlinked structures of the Internet and relational databases. Likewise, in many domains a background knowledge in the form of relational logic rules or rich graph-based structures is often available, yet impossible or very difficult to exploit with the standard deep learning models.

To address this issue, we introduce a declarative deep relational learning framework called Lifted Relational Neural Networks (LRNNs). The main idea underlying the framework is to approach the neural networks through the *lifted modeling* paradigm, known otherwise from Statistical Relational Learning (SRL), where it is used to exploit *symmetries* in learning problems. Similarly to lifted graphical models from SRL, LRNNs are then represented as sets of *weighted relational logic* rules, used to describe the structure of a given learning setting. 

As set out, we demonstrate that this paradigm allows for effective end-to-end neural learning with relational data and knowledge. The encoding through the weighted relational logic rules then provides flexible means for implementing a wide variety of novel modeling concepts incorporating various latent relational patterns. Notably, these also elegantly cover contemporary deep convolutional models, such as Graph Neural Networks, as a simple special case. We explain how to easily generalize these state-of-the-art models towards higher expressiveness, and also demonstrate the general LRNN framework on various practical learning scenarios and benchmarks, including computational efficiency.

Additionally, we introduce several enhancements to the framework. Firstly, we present an automated structure learning of the relational rules, composing the lifted models. Secondly, we introduce two principled optimization techniques used to scale up the integrative framework from both the logical and neural learning perspectives. Both the optimization methods are then effective also separately in the respective approaches to learning. Lastly, we demonstrate the framework on selected use cases in different domains.

[full PDF](/files/dissertation.pdf)

cite as:
```
@article{sir2020deep,
          title={Deep Learning with Relational Logic Representations},
          author={\v{S}{\'i}r, Gustav},
          journal={Czech Technical University press, Ph.D. thesis.},
          year={2020}
}
```