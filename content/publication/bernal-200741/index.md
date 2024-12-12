---
title: An RBF meshless method for injection molding modelling

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

date: '2007-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.954612Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Lecture Notes in Computational Science and Engineering*'
publication_short: ''

doi: 10.1007/978-3-540-46222-4_3

abstract: Recently, very intensive efforts have been devoted to develop meshless or
  element free methods that eliminate the need of element connectivity in the solution
  of PDEs. The motivation is to cut down modelling costs in industrial applications
  by avoiding the labor intensive step of mesh generation. In addition, these methods
  are particularly attractive in problems with moving interfaces since no remeshing
  is necessary. In this paper, we address the problem of injection molding described
  as a free boundary problem defined by conservation equations for mass, momentum
  and energy. This model can be dramatically simplified assuming that the mould is
  thin so that a Hele-Shaw approximation can be used. In this case the momentum equation
  is just a 2D elliptic equation whose solution yields the pressure distribution in
  the filled region of the mould. From this pressure field, the velocity distribution
  can be computed and the location of the advancing front can be updated. Therefore,
  this problem is very well suited to meshfree techniques and, in this paper, we use
  a radial basis function (RBF) method which is based on the interpolation and collocation
  of global shape functions, and for simplicity assume a Newtonian fluid so that the
  model is linear. In particular, we use multiquadric (MQ) RBFs which have been shown
  to have exponential convergence. To advance the front we use a level set method
  which is very efficient for this type of problems because it is very fast and can
  handle both front collisions and front break-ups without difficulty.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-77951205890&doi=10.1007%2f978-3-540-46222-4_3&partnerID=40&md5=500dc9214dfb4129ace2f368a1cfaf65
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
