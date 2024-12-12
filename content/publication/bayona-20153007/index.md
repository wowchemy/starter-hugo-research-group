---
title: A 3-D RBF-FD solver for modeling the atmospheric global electric circuit with
  topography (GEC-RBFFD v1.0)

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- V. Bayona
- N. Flyer
- G.M. Lucas
- A.J.G. Baumgaertner

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2015-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:36.655176Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Geoscientific Model Development*'
publication_short: ''

doi: 10.5194/gmd-8-3007-2015

abstract: A numerical model based on radial basis function-generated finite differences
  (RBF-FD) is developed for simulating the global electric circuit (GEC) within the
  Earth's atmosphere, represented by a 3-D variable coefficient linear elliptic partial
  differential equation (PDE) in a spherically shaped volume with the lower boundary
  being the Earth's topography and the upper boundary a sphere at 60 km. To our knowledge,
  this is (1) the first numerical model of the GEC to combine the Earth's topography
  with directly approximating the differential operators in 3-D space and, related
  to this, (2) the first RBF-FD method to use irregular 3-D stencils for discretization
  to handle the topography. It benefits from the mesh-free nature of RBF-FD, which
  is especially suitable for modeling high-dimensional problems with irregular boundaries.
  The RBF-FD elliptic solver proposed here makes no limiting assumptions on the spatial
  variability of the coefficients in the PDE (i.e., the conductivity profile), the
  right hand side forcing term of the PDE (i.e., distribution of current sources)
  or the geometry of the lower boundary. © Author(s) 2015.

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-84943174299&doi=10.5194%2fgmd-8-3007-2015&partnerID=40&md5=9021751828d0227624ecc958a463b4ff
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
