---
title: A distributed Monte Carlo based linear algebra solver applied to the analysis
  of large complex networks

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- F. Magalhães
- J. Monteiro
- J.A. Acebrón
- J.R. Herrero

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.449931Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Future Generation Computer Systems*'
publication_short: ''

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

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: 
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85116028771&doi=10.1016%2fj.future.2021.09.014&partnerID=40&md5=12786d1247b9ca22474aa2aea81e169b
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
