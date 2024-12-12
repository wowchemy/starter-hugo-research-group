---
title: Finite-element method for elastic wave propagation

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- F.J. Seron
- F.J. Sanz
- M. Kindelan
- J.I. Badal

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '1990-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:37.320591Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Communications in Applied Numerical Methods*'
publication_short: ''

doi: 10.1002/cnm.1630060505

abstract: The computational aspects of the finite-element method for the elastic wave
  equations are considered. The necessary numerical techniques are analysed from the
  point of view of accuracy, performance and storage requirements when implemented
  in scalar and vector processors with large storage capacity. The method is implemented
  on an IBM 3090 with vector facility. We consider five different time integration
  schemes (explicit and implicit central difference, Houbolt, constant average acceleration
  and Wilson), and in the implicit case, both direct (Gaussian decomposition) and
  iterative (successive over-relaxation, Jacobi semi-iterative, Jacobi conjugate gradient)
  sparse linear system solvers. These solvers are taken from the ITPACK-2C and ESSL
  libraries using in each case the adequate representation scheme; skyline, row-wise
  and compressed diagonal. It is concluded that constant average acceleration and
  explicit central difference are the most adequate integration methods and Jacobi
  conjugate gradient is the most efficient solver.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-0025462696&doi=10.1002%2fcnm.1630060505&partnerID=40&md5=8b54442be799a73507533f94034a6cf4
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
