---
title: Frequency optimized RBF-FD for wave equations

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- M. Kindelan
- D. Álvarez
- P. Gonzalez-Rodriguez

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2018-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.556783Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Journal of Computational Physics*'
publication_short: ''

doi: 10.1016/j.jcp.2018.06.006

abstract: We present a method to obtain optimal RBF-FD formulas which maximize their
  frequency range of validity. The optimization is based on the idea of keeping an
  error of interest (dispersion, phase or group velocity errors) below a given threshold
  for a wavenumber interval as large as possible. To find the weights of these optimal
  finite difference formulas we solve an optimization problem. In a previous work
  we developed a method to optimize the frequency range of validity for finite difference
  weights. That method required to solve a system of nonlinear equations with as many
  unknowns as half of the number of weights, which is a very hard task when the number
  of nodes gets large. The current method requires solving an optimization problem
  with only one parameter, which makes finding a global minimum easier, and thus can
  be used for bigger stencils. We also study which of the standard RBF are more appropriate
  for this problem and introduce a new RBF that depends on two parameters. This new
  RBF improves the resulting frequency response of the RBF-FD methods while keeping
  the cost of the optimization problem low. © 2018 Elsevier Inc.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85048391843&doi=10.1016%2fj.jcp.2018.06.006&partnerID=40&md5=d112ddf8335fa44977162f5fb8503286
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
