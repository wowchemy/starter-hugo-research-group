---
title: Comparison of Moving Least Squares and RBF+poly for Interpolation and Derivative
  Approximation

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- V. Bayona

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2019-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.525615Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Journal of Scientific Computing*'
publication_short: ''

doi: 10.1007/s10915-019-01028-8

abstract: The combination of polyharmonic splines (PHS) with high degree polynomials
  (PHS+poly) has recently opened new opportunities for radial basis function generated
  finite difference approximations. The PHS+poly formulation, which relies on a polynomial
  least squares fitting to enforce the local polynomial reproduction property, resembles
  somehow the so-called moving least squares (MLS) method. Although these two meshfree
  approaches are increasingly used nowadays, no direct comparison has been done yet.
  The present study aims to fill this gap, focusing on scattered data interpolation
  and derivative approximation. We first review the MLS approach and show that under
  some mild assumptions PHS+poly can be formulated analogously. Based on heuristic
  perspectives and numerical demonstrations, we then compare their performances in
  1-D and 2-D. One key result is that, as previously found for PHS+poly, MLS can also
  overcome the edge oscillations (Runge’s phenomenon) by simply increasing the stencil
  size for a fixed polynomial degree. This is, however, controlled by a weighted least
  squares fitting which fails for high polynomial degrees. Overall, PHS+poly is found
  to perform superior in terms of accuracy and robustness. © 2019, Springer Science+Business
  Media, LLC, part of Springer Nature.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85070270289&doi=10.1007%2fs10915-019-01028-8&partnerID=40&md5=3d1fc337f26385e86d208ff81891c3fe
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
