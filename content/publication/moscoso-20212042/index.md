---
title: Fast Signal Recovery from Quadratic Measurements

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- M. Moscoso
- A. Novikov
- G. Papanicolaou
- C. Tsogka

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.485804Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Signal Processing*'
publication_short: ''

doi: 10.1109/TSP.2021.3067140

abstract: We present a novel approach for recovering a sparse signal from quadratic
  measurements corresponding to a rank-one tensorization of the data vector. Such
  quadratic measurements, referred to as interferometric or cross-correlated data,
  naturally arise in many fields such as remote sensing, spectroscopy, holography
  and seismology. Compared to the sparse signal recovery problem that uses linear
  measurements, the unknown in this case is a matrix formed by the cross correlations
  of the sought signal. This creates a bottleneck for the inversion since the number
  of unknowns grows quadratically with the dimension of the signal. The main idea
  of the proposed approach is to reduce the dimensionality of the problem by recovering
  only the diagonal of the unknown matrix, whose dimension grows linearly with the
  size of the signal, and use an efficient Noise Collector to absorb the cross-correlated
  data that come from the off-diagonal elements of this matrix. These elements do
  not carry extra information about the support of the signal, but significantly contribute
  to these data. With this strategy, we recover the unknown matrix by solving a convex
  linear problem whose cost is similar to the one that uses linear measurements. Our
  theory shows that the proposed approach provides exact support recovery when the
  data is not too noisy, and that there are no false positives for any level of noise.
  It also demonstrates that the level of sparsity that can be recovered scales almost
  linearly with the number of data. The numerical experiments presented in the paper
  corroborate these findings. © 1991-2012 IEEE.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85103271136&doi=10.1109%2fTSP.2021.3067140&partnerID=40&md5=237b2603c3910c97e6374f8e2cb09ac8
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
