---
title: "Stacked Structure Learning for Lifted Relational Neural Networks"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-5
excerpt: 'A structure learning extension of the LRNN concept - we won the **best paper** of the conference with it.'
date: 2017-05-17
venue: 'International Conference on Inductive Logic Programming'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-319-78090-0_10'

---
**G Šourek, M Svatoš, F Železný, S Schockaert, O Kuželka**

Lifted Relational Neural Networks (LRNNs) describe relational domains using weighted first-order rules which act as templates for constructing feed-forward neural networks. While previous work has shown that using LRNNs can lead to state-of-the-art results in various ILP tasks, these results depended on hand-crafted rules. In this paper, we extend the framework of LRNNs with structure learning, thus enabling a fully automated learning process. Similarly to many ILP methods, our structure learning algorithm proceeds in an iterative fashion by top-down searching through the hypothesis space of all possible Horn clauses, considering the predicates that occur in the training examples as well as invented soft concepts entailed by the best weighted rules found so far. In the experiments, we demonstrate the ability to automatically induce useful hierarchical soft concepts leading to deep LRNNs with a competitive predictive power.
cite as:
```
@inproceedings{vsourek2017stacked,
  title={Stacked structure learning for lifted relational neural networks},
  author={{\v{S}}ourek, Gustav and Svato{\v{s}}, Martin and {\v{Z}}elezn{\`y}, Filip and Schockaert, Steven and Ku{\v{z}}elka, Ond{\v{r}}ej},
  booktitle={International Conference on Inductive Logic Programming},
  pages={140--151},
  year={2017},
  organization={Springer}
}
```