---
title: "Beyond Graph Neural Networks with Lifted Relational Neural Networks"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-2
excerpt: 'We show how the Lifted Relational Neural Networks concept covers the Graph Neural Networks concept (and more)'
date: 2021-05-17
venue: 'Machine Learning Journal'
paperurl: 'https://arxiv.org/pdf/2007.06286.pdf'
---
**G Sourek, F Zelezny, O Kuzelka**

We introduce a declarative differentiable programming framework, based on the language of Lifted Relational Neural Networks, where small parameterized logic programs are used to encode deep relational learning scenarios through the underlying symmetries. When presented with relational data, such as various forms of graphs, the logic program interpreter dynamically unfolds differentiable computational graphs to be used for the program parameter optimization by standard means. Following from the declarative, relational logic-based encoding, this results into a unified representation of a wide range of neural models in the form of compact and elegant learning programs, in contrast to the existing procedural approaches operating directly on the computational graph level.
We illustrate how this idea can be used for a concise encoding of existing advanced neural architectures, with the main focus on Graph Neural Networks (GNNs). Importantly, using the framework, we also show how the contemporary GNN models can be easily extended towards higher expressiveness in various ways. In the experiments, we demonstrate correctness and computation efficiency through comparison against specialized GNN frameworks, while shedding some light on the learning performance of the existing GNN models.

```
@article{sourek2020beyond,
         title={Beyond Graph Neural Networks with Lifted Relational Neural Networks},
         author={Sourek, Gustav and Zelezny, Filip and Kuzelka, Ondrej},
         journal={arXiv preprint arXiv:2007.06286},
         year={2020}
}
```