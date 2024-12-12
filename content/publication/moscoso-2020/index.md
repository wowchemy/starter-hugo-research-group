---
title: Imaging with highly incomplete and corrupted data

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

date: '2020-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.516761Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Inverse Problems*'
publication_short: ''

doi: 10.1088/1361-6420/ab5a21

abstract: We consider the problem of imaging sparse scenes from a few noisy data using
  an ℓ1-minimization approach. This problem can be cast as a linear system of the
  form Ap = b, where A is an N × K measurement matrix. We assume that the dimension
  of the unknown sparse vector p ϵ ℂk is much larger than the dimension of the data
  vector b ϵ ℂN, i.e. K Gt; N. We provide a theoretical framework that allows us to
  examine under what conditions the ℓ1-minimization problem admits a solution that
  is close to the exact one in the presence of noise. Our analysis shows that ℓ1-minimization
  is not robust for imaging with noisy data when high resolution is required. To improve
  the performance of ℓ1-minimization we propose to solve instead the augmented linear
  system [A|C]p = b, where the N × σ matrix C is a noise collector. It is constructed
  so as its column vectors provide a frame on which the noise of the data, a vector
  of dimension N, can be well approximated. Theoretically, the dimension σ of the
  noise collector should be eN which would make its use not practical. However, our
  numerical results illustrate that robust results in the presence of noise can be
  obtained with a large enough number of columns σ ≺∼ 10K. © 2020 IOP Publishing Ltd.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85080071452&doi=10.1088%2f1361-6420%2fab5a21&partnerID=40&md5=212247134257d02c2c96a827d50bbbfa
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
