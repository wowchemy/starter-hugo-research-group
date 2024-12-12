---
title: A highly parallel algorithm for computing the action of a matrix exponential
  on a vector based on a multilevel Monte Carlo method

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- J.A. Acebrón
- J.R. Herrero
- J. Monteiro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.490364Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computers and Mathematics with Applications*'
publication_short: ''

doi: 10.1016/j.camwa.2020.02.013

abstract: A novel algorithm for computing the action of a matrix exponential over
  a vector is proposed. The algorithm is based on a multilevel Monte Carlo method,
  and the vector solution is computed probabilistically generating suitable random
  paths which evolve through the indices of the matrix according to a suitable probability
  law. The computational complexity is proved in this paper to be significantly better
  than the classical Monte Carlo method, which allows the computation of much more
  accurate solutions. Furthermore, the positive features of the algorithm in terms
  of parallelism were exploited in practice to develop a highly scalable implementation
  capable of solving some test problems very efficiently using high performance supercomputers
  equipped with a large number of cores. For the specific case of shared memory architectures
  the performance of the algorithm was compared with the results obtained using an
  available Krylov-based algorithm, outperforming the latter in all benchmarks analyzed
  so far. © 2020 Elsevier Ltd

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85081258256&doi=10.1016%2fj.camwa.2020.02.013&partnerID=40&md5=0296e2be6779e70ab39c5c5fd18a83f4
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
