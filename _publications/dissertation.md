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

### Rewies

I gratefully acknowledge the thesis reviewers for their time devoted to my PhD defense:

 - [prof. Hendrik Blockeel](https://scholar.google.com/citations?user=Eq5sUNpp0gwC&hl=en)  (Katholieke Universiteit, Leuven)
 - [prof. Ashwin Srinivasan](https://scholar.google.com.au/citations?user=zpNTeogAAAAJ&hl=en)   (BITS-Pilani, Goa India )
 - [Dr. Pasquale Minervini, Ph.D.](https://scholar.google.it/citations?user=9sk6CSgAAAAJ&hl=it)    (University College London)
 - [Dr. Mathias Niepert, Ph.D.](https://scholar.google.com/citations?user=p5vLzq0AAAAJ&hl=cs)    (NEC Labs Europe)


##### Excerpts from the reviews

- _The work of Mr. Šír is of the highest quality: it exceeds the standards typically imposed on PhD dissertations in computer science even at the best universities._

- _...it is internationally recognized as one of the main challenges in the field of artificial intelligence these days. This dissertation
   contains several highly original contributions that substantially advance the state of
   the art in this area._
   
- _...What I find particularly strong in this thesis is that, contrary to a lot of contemporary
      work, the main results do not lie in small quantitative improvements [...], but on deep conceptual innovations that lead to a broadly applicable and
      easy-to-use approach._
   
- _The originality, technical depth and technical accuracy of the work are excellent and meet the highest standards of PhD research._

- _...the dissertation has made important and novel contributions to the field of neural-
   symbolic learning._

- _The thesis is extremely well-written and instructive, and the proposed models and experiments are deeply interesting
   and inspiring: I am happy to provide a very positive review._
   
- _In general, the thesis is excellent and I would rate it as a top thesis in the area of neuro-symbolic learning. I am extremely impressed by both the breadth and depth of the thesis
   and the level of clarity and detail followed throughout._



- _Overall, this is an excellent thesis and I am very proud that I was asked to review it._

<br>
---
cite as:
```
@article{sir2020deep,
          title={Deep Learning with Relational Logic Representations},
          author={\v{S}{\'i}r, Gustav},
          journal={Czech Technical University press, Ph.D. thesis.},
          year={2020}
}
```

#### Acknowledgment

I'm deeply grateful to all the people who helped me to successfully complete the PhD stage, especially to my supervisor specialist [Ondrej Kuzelka](https://ida.fel.cvut.cz/~kuzelka/) for all his insights, guidance and support throughout the whole journey.
