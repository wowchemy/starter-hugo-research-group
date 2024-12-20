---
title: A distributed Monte Carlo based linear algebra solver applied to the analysis
  of large complex networks
authors:
- F. Magalhães
- J. Monteiro
- J.A. Acebrón
- J.R. Herrero
date: '2022-01-01'
publishDate: '2024-12-20T11:30:45.238989Z'
publication_types:
- article-journal
publication: '*Future Generation Computer Systems*'
doi: 10.1016/j.future.2021.09.014
abstract: Methods based on Monte Carlo for solving linear systems have some interesting
  properties which make them, in many instances, preferable to classic methods. Namely,
  these statistical methods allow the computation of individual entries of the output,
  hence being able to handle problems where the size of the resulting matrix would
  be too large. In this paper, we propose a distributed linear algebra solver based
  on Monte Carlo. The proposed method is based on an algorithm that uses random walks
  over the system's matrix to calculate powers of this matrix, which can then be used
  to compute a given matrix function. Distributing the matrix over several nodes enables
  the handling of even larger problem instances, however it entails a communication
  penalty as walks may need to jump between computational nodes. We have studied different
  buffering strategies and provide a solution that minimizes this overhead and maximizes
  performance. We used our method to compute metrics of complex networks, such as
  node centrality and resolvent Estrada index. We present results that demonstrate
  the excellent scalability of our distributed implementation on very large networks,
  effectively providing a solution to previously unreachable problem instances. ©
  2021 Elsevier B.V.
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85116028771&doi=10.1016%2fj.future.2021.09.014&partnerID=40&md5=12786d1247b9ca22474aa2aea81e169b
---
