---
title: A hybrid probabilistic domain decomposition algorithm suited for very large-scale
  elliptic PDEs

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- F. Bernal
- J. Morón-Vidal
- J.A. Acebrón

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2023-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.432553Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computers and Mathematics with Applications*'
publication_short: ''

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85165637492&doi=10.1016%2fj.camwa.2023.07.004&partnerID=40&md5=187efcbbb1da4a311d79e75d36efa597
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
