---
title: A hybrid probabilistic domain decomposition algorithm suited for very large-scale
  elliptic PDEs
authors:
- F. Bernal
- J. Morón-Vidal
- J.A. Acebrón
date: '2023-01-01'
publishDate: '2024-12-20T11:30:45.224049Z'
publication_types:
- article-journal
publication: '*Computers and Mathematics with Applications*'
doi: 10.1016/j.camwa.2023.07.004
abstract: State of the art domain decomposition algorithms for large-scale boundary
  value problems (with M≫1 degrees of freedom) suffer from bounded strong scalability
  because they involve the synchronisation and communication of workers inherent to
  iterative linear algebra. Here, we introduce PDDSparse, a different approach to
  scientific supercomputing which relies on a “Feynman-Kac formula for domain decomposition”.
  Concretely, the interfacial values (only) are determined by a stochastic, highly
  sparse linear system G(ω)u→=b→(ω) of size O(M), whose coefficients are constructed
  with Monte Carlo simulations—hence embarrassingly in parallel. In addition to a
  wider scope for strong scalability in the deep supercomputing regime, PDDSparse
  has built-in fault tolerance and is ideally suited for GPUs. A proof of concept
  example with up to 1536 cores is discussed in detail. © 2023 The Author(s)
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85165637492&doi=10.1016%2fj.camwa.2023.07.004&partnerID=40&md5=187efcbbb1da4a311d79e75d36efa597
---
