---
title: An unfitted radial basis function generated finite difference method applied
  to thoracic diaphragm simulations

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- I. Tominec
- P.-F. Villard
- E. Larsson
- V. Bayona
- N. Cacciani

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.436797Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Journal of Computational Physics*'
publication_short: ''

doi: 10.1016/j.jcp.2022.111496

abstract: The thoracic diaphragm is the muscle that drives the respiratory cycle of
  a human being. Using a system of partial differential equations (PDEs) that models
  linear elasticity we compute displacements and stresses in a two-dimensional cross
  section of the diaphragm in its contracted state. The boundary data consists of
  a mix of displacement and traction conditions. If these are imposed as they are,
  and the conditions are not compatible, this leads to reduced smoothness of the solution.
  Therefore, the boundary data is first smoothed using the least-squares radial basis
  function generated finite difference (RBF-FD) framework. Then the boundary conditions
  are reformulated as a Robin boundary condition with smooth coefficients. The same
  framework is also used to approximate the boundary curve of the diaphragm cross
  section based on data obtained from a slice of a computed tomography (CT) scan.
  To solve the PDE we employ the unfitted least-squares RBF-FD method. This makes
  it easier to handle the geometry of the diaphragm, which is thin and non-convex.
  We show numerically that our solution converges with high-order towards a finite
  element solution evaluated on a fine grid. Through this simplified numerical model
  we also gain an insight into the challenges associated with the diaphragm geometry
  and the boundary conditions before approaching a more complex three-dimensional
  model. © 2022 The Author(s)

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-85135940010&doi=10.1016%2fj.jcp.2022.111496&partnerID=40&md5=6205f7e072282a3e97ad539db3339779
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
