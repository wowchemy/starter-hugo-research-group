---
title: Highly efficient numerical algorithm based on random trees for accelerating
  parallel Vlasov-Poisson simulations

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- J.A. Acebrón
- T. Rodríguez-Rozas

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2013-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.709628Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Journal of Computational Physics*'
publication_short: ''

doi: 10.1016/j.jcp.2013.05.025

abstract: An efficient numerical method based on a probabilistic representation for
  the Vlasov-Poisson system of equations in the Fourier space has been derived. This
  has been done theoretically for arbitrary dimensional problems, and particularized
  to unidimensional problems for numerical purposes. Such a representation has been
  validated theoretically in the linear regime comparing the solution obtained with
  the classical results of the linear Landau damping.The numerical strategy followed
  requires generating suitable random trees combined with a Padé approximant for approximating
  accurately a given divergent series. Such series are obtained by summing the partial
  contributions to the solution coming from trees with arbitrary number of branches.
  These contributions, coming in general from multi-dimensional definite integrals,
  are efficiently computed by a quasi-Monte Carlo method. It is shown how the accuracy
  of the method can be effectively increased by considering more terms of the series.The
  new representation was used successfully to develop a Probabilistic Domain Decomposition
  method suited for massively parallel computers, which improves the scalability found
  in classical methods. Finally, a few numerical examples based on classical phenomena
  such as the non-linear Landau damping, and the two streaming instability are given,
  illustrating the remarkable performance of the algorithm, when compared the results
  with those obtained using a classical method. © 2013 Elsevier Inc.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-84879167474&doi=10.1016%2fj.jcp.2013.05.025&partnerID=40&md5=a6faf90e16c0bed2c200048e317af3a5
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
