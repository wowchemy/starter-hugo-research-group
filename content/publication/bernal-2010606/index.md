---
title: Radial basis function solution of the Motz problem

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- F. Bernal
- M. Kindelan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2010-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.793059Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Engineering Computations (Swansea, Wales)*'
publication_short: ''

doi: 10.1108/02644401011050903

abstract: The Motz problem can be considered as a benchmark problem for testing the
  performance of numerical methods in the solution of elliptic problems with boundary
  singularities. The purpose of this paper is to address the solution of the Motz
  problem using the radial basis function (RBF) method, which is a truly meshfree
  scheme. Design/methodology/approach - Both the global RBF collocation method (also
  known as Kansa's method) and the recently proposed local RBF-based differential
  quadrature (LRBFDQ) method are considered. In both cases, it is shown that the accuracy
  of the solution can be significantly increased by using special functions which
  capture the behavior of the singularity. In the case of global collocation, the
  functional space spanned by the RBF is enlarged by adding singular functions which
  capture the behavior of the local singular solution. In the case of local collocation,
  the problem is modified appropriately in order to eliminate the singularities from
  the formulation. Findings - The paper shows that the exponential convergence both
  with increasing resolution and increasing shape parameter, which is typical of the
  RBF method, is lost in problems containing singularities.The accuracyof the solution
  can be increased bycollocation of the partial differential equation (PDE) at boundary
  nodes.However, in order to restore the exponential convergence of theRBFmethod,
  it is necessary to use special functions which capture the behavior of the solution
  near the discontinuity. Practical implications - The paper uses Motz's problem as
  a prototype for problems described byelliptic partial differential equations with
  boundary singularities. However, the results obtained in the paper are applicable
  to a wide range of problems containing boundaries with conditions which change from
  Dirichlet to Neumann, thus leading to singularities in the first derivatives. Originality/value
  - The paper shows that both the global RBF collocation method and the LRBFDQ method,
  are truly meshless methods which can be very useful for the solution of elliptic
  problems with boundary singularities. In particular, when complemented with special
  functions that capture the behavior of the solution near the discontinuity, the
  method exhibits exponential convergence both with resolution and with shape parameter.
  © Emerald Group Publishing Limited.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-77954764566&doi=10.1108%2f02644401011050903&partnerID=40&md5=a75de7b03cbe84af3809a6f8558657f4
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
