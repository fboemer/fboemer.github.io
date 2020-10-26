---
title: "ngraph-HE: A Graph Compiler for Deep Learning on Homomorphically Encrypted Data"
collection: publications
permalink: /publications/ngraph-he
excerpt: 'exceprt'
# date: 2015-10-01
venue: 'CF 2019: Proceedings of the 16th ACM International Conference on Computing Frontiers'
paperurl: 'https://dl.acm.org/doi/10.1145/3310273.3323047'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
authors: ' <b>Fabian Boemer</b>, Yixing Lao, Rosario Cammarota, Casimir Wierzynski'
abstract: "Homomorphic encryption (HE)---the ability to perform computation on encrypted data---is an attractive remedy to increasing concerns about data privacy in deep learning (DL). However, building DL models that operate on ciphertext is currently labor-intensive and requires simultaneous expertise in DL, cryptography, and software engineering. DL frameworks and recent advances in graph compilers have greatly accelerated the training and deployment of DL models to various computing platforms. We introduce nGraph-HE, an extension of nGraph, Intel's DL graph compiler, which enables deployment of trained models with popular frameworks such as TensorFlow while simply treating HE as another hardware target. Our graph-compiler approach enables HE-aware optimizations- implemented at compile-time, such as constant folding and HE-SIMD packing, and at run-time, such as special value plaintext bypass. Furthermore, nGraph-HE integrates with DL frameworks such as TensorFlow, enabling data scientists to benchmark DL models with minimal overhead."
---

Fabian Boemer, Yixing Lao, Rosario Cammarota, Casimir Wierzynski

**Abstract**
Homomorphic encryption (HE)---the ability to perform computation on encrypted data---is an attractive remedy to increasing concerns about data privacy in deep learning (DL). However, building DL models that operate on ciphertext is currently labor-intensive and requires simultaneous expertise in DL, cryptography, and software engineering. DL frameworks and recent advances in graph compilers have greatly accelerated the training and deployment of DL models to various computing platforms. We introduce nGraph-HE, an extension of nGraph, Intel's DL graph compiler, which enables deployment of trained models with popular frameworks such as TensorFlow while simply treating HE as another hardware target. Our graph-compiler approach enables HE-aware optimizations- implemented at compile-time, such as constant folding and HE-SIMD packing, and at run-time, such as special value plaintext bypass. Furthermore, nGraph-HE integrates with DL frameworks such as TensorFlow, enabling data scientists to benchmark DL models with minimal overhead.
