---
title: A stochastic method for solving time-fractional differential equations

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- N.L. Guidotti
- J.A. Acebrón
- J. Monteiro

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.402134Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computers and Mathematics with Applications*'
publication_short: ''

doi: 10.1016/j.camwa.2024.02.020

abstract: We present a stochastic method for efficiently computing the solution of
  time-fractional partial differential equations (fPDEs) that model anomalous diffusion
  problems of the subdiffusive type. After discretizing the fPDE in space, the ensuing
  system of fractional linear equations is solved resorting to a Monte Carlo evaluation
  of the corresponding Mittag-Leffler matrix function. This is accomplished through
  the approximation of the expected value of a suitable multiplicative functional
  of a stochastic process, which consists of a Markov chain whose sojourn times in
  every state are Mittag-Leffler distributed. The resulting algorithm is able to calculate
  the solution at conveniently chosen points in the domain with high efficiency. In
  addition, we present how to generalize this algorithm in order to compute the complete
  solution. For several large-scale numerical problems, our method showed remarkable
  performance in both shared-memory and distributed-memory systems, achieving nearly
  perfect scalability up to 16,384 CPU cores. © 2024 Elsevier Ltd

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85186270872&doi=10.1016%2fj.camwa.2024.02.020&partnerID=40&md5=5fa8eeeffae23798318d15bd7c1a3140
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
