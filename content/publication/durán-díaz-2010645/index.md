---
title: Parallelizing a hybrid finite element-boundary integral method for the analysis
  of scattering and radiation of electromagnetic waves
authors:
- R. Durán Díaz
- R. Rico
- L.E. García-Castillo
- I. Gómez-Revuelto
- J.A. Acebrón
- I. Martínez-Fernández
date: '2010-01-01'
publishDate: '2024-12-20T11:30:45.540490Z'
publication_types:
- article-journal
publication: '*Finite Elements in Analysis and Design*'
doi: 10.1016/j.finel.2010.03.004
abstract: 'This paper presents the practical experience of parallelizing a simulator
  of general scattering and radiation electromagnetic problems. The simulator stems
  from an existing sequential simulator in the frequency domain, which is based on
  a finite element analysis. After the analysis of a test case, two steps were carried
  out: first, a \"hand-crafted\" code parallelization of a convolution-type operation
  was developed within the kernel of the simulator. Second, the sequential HSL library,
  used in the existing simulator, was replaced by the parallel MUMPS (MUltifrontal
  Massively Parallel sparse direct Solver) library in order to solve the associated
  linear algebra problem in parallel. Such a library allows for the distribution of
  the factorized matrix and some of the computational load among the available processors.
  A test problem and three realistic (in terms of the number of unknowns) cases have
  been run using the parallelized version of the code, and the results are presented
  and discussed focusing on the memory usage and achieved speed-up. © 2010 Elsevier
  B.V. All rights reserved.'
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-77955267772&doi=10.1016%2fj.finel.2010.03.004&partnerID=40&md5=7412f863f17f8173616e65273ca2c3be
---
