---
type: docs
bookToc: True
weight: 1
---

# **Mixture-of-Depths: Dynamically allocating compute in transformer-based language models**
*Authors: Dativd Raposo(Google DeepMind) and Adam Santoro(Google DeepMind) et.al*

“Choice and concentration” is an effective strategies for completing tasks with overall success. It is not necessary to consume same amount of effort and time into all problems. If we expend our energy on trivial issues, we may fail to concentrate on what truly matters. Similary, a technique was introduced that allows languge models to allocate less budget to non-essential tokens instead of focusing equally on all tokens.

The tremendous technique developed by Google DeepMind Researchers is called Miture-of-Depths, or MoD for short. In this blog post, we take a look at building blocks of MoD and how they works.

## Table of Contents

- [Overview to Mixture-of-Depths (MoD)]
- [Conditional computation methods for transformers]
- [Capacity based routing schemes]
- [Implementation detail]
- [Open source MoD]
- [Conclusion and discussion]
- [Some resources]
