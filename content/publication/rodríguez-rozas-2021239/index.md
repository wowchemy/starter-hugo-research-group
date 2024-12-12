---
title: The PDD Method for Solving Linear, Nonlinear, and Fractional PDEs Problems

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Á. Rodríguez-Rozas
- J.A. Acebrón
- R. Spigler

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.481143Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*SEMA SIMAI Springer Series*'
publication_short: ''

doi: 10.1007/978-3-030-69236-0_13

abstract: 'We review the Probabilistic Domain Decomposition (PDD) method for the numerical
  solution of linear and nonlinear Partial Differential Equation (PDE) problems. This
  Domain Decomposition (DD) method is based on a suitable probabilistic representation
  of the solution given in the form of an expectation which, in turns, involves the
  solution of a Stochastic Differential Equation (SDE). While the structure of the
  SDE depends only upon the corresponding PDE, the expectation also depends upon the
  boundary data of the problem. The method consists of three stages: (i) only few
  values of the sought solution are solved by Monte Carlo or Quasi-Monte Carlo at
  some interfaces; (ii) a continuous approximation of the solution over these interfaces
  is obtained via interpolation; and (iii) prescribing the previous (partial) solutions
  as additional Dirichlet boundary conditions, a fully decoupled set of sub-problems
  is finally solved in parallel. For linear parabolic problems, this is based on the
  celebrated Feynman-Kac formula, while for semilinear parabolic equations requires
  a suitable generalization based on branching diffusion processes. In case of semilinear
  transport equations and the Vlasov-Poisson system, a generalization of the probabilistic
  representation was also obtained in terms of the Method of Characteristics (characteristic
  curves). Finally, we present the latest progress towards the extension of the PDD
  method for nonlocal fractional operators. The algorithm notably improves the scalability
  of classical algorithms and is suited to massively parallel implementation, enjoying
  arbitrary scalability and fault tolerance properties. Numerical examples conducted
  in 1D and 2D, including some for the KPP equation and Plasma Physics, are given.
  © 2021, The Author(s), under exclusive license to Springer Nature Switzerland AG.'

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85112594207&doi=10.1007%2f978-3-030-69236-0_13&partnerID=40&md5=64efe3919658a110afe3f2acbe3bf2ae
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
