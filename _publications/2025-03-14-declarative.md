---
title: "Towards Declarative Blockchains: A SHACL-Based Model for Robust and Efficient Transactions"
collection: publications
category: conferences
permalink: /publication/2025-03-14-declarative
excerpt: 'Proposed modeling blockchain transactions with Shape Constraint Languages to reduce errors from imperative smart contracts.'
date: 2025-06-02
venue: 'IEEE International Conference on Blockchain and Cryptocurrency (ICBC)'

---

<!-- **Extended Paper**: [Arxiv](./) 

**Artifact**: [GitHub](https://github.com/wspr-ncsu/jaeger) and [Zenodo](https://zenodo.org/doi/10.5281/zenodo.12733869) -->

**Abstract**: While blockchains provide robust distributed transaction processing, their native transaction capabilities are limited, typically requiring smart contracts for extended functionality. However, smart contracts introduce significant robustness and efficiency challenges as imperative programs. This paper introduces an algebraic transaction model based on declarative specifications using SHACL (Shapes Constraint Language) constraints within a stratified architecture. This approach enables automated reasoning about transaction properties, supports composition of transaction primitives, and formulates validation as a graph pattern constraint-checking problem. Through an implementation on BigChainDB and comparative evaluation against Quorum, we demonstrate significant improvements in transaction throughput (up to 3500\%) while maintaining equivalent functionality, establishing our SHACL-based algebraic transaction model as a robust and efficient alternative to smart contracts.


#### BibTex

```Bibtex
@article{towardsdeclarativeblockchains,
  title = {Towards Declarative Blockchains: A SHACL-Based Model for Robust and Efficient Transactions},
  author = {Kemafor Anyanwu, Sogolsadat Mansouri, David Adei},
  year = {2025},
  journal = {Proceedings of the IEEE International Conference on Blockchain and Cryptocurrency (ICBC)},
}
```