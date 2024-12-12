---
title: Regularity conforming neural networks for PDEs.
event: Seminario GMNA
event_url: 

location: Sala de Seminarios del Departamento de Matemáticas (2.2.D08)
address:
  street: 
  city: 
  region: 
  postcode: 
  country: 

summary: ''
abstract: 'Neural Networks (NNs) are becoming more commonly applied as discretised function spaces for solving Partial Differential Equations (PDEs). Whilst the Universal Approximation Theorem guarantees that a sufficiently large NN can approximate Sobolev functions – the natural functions that arise in PDEs, we will demonstrate that in practice, low-regularity solutions can lead to convergence issues during training. To overcome this, we propose the use of regularity-conforming architectures, where a priori regularity information is built into the NN. In addition, such architectures are inherently explainable, allowing the definition of novel types of loss function. We use a 2D transmission problem with discontinuous materials as our case study. This example is used in several application domains, e.g., geophysics, and at the same time we know precisely several aspects of its regularity along the domain. The solutions may admit power-like singularities and discontinuities in the gradient across material interfaces. In the classical L-shape problem, our proposed architecture improves the H1-error by a factor of ten with respect to the use of a classical architecture. In the case of four distinct materials, where both jump discontinuities in the derivative and power-type singularities are present, our explainable architecture permits the definition of a PINNs-type loss based on the strong formulation of the PDE with an interface condition, obtaining H1-relative errors of 0.5%. This is a joint work with David Pardo (UPV/EHU and BCAM) and Judit Muñoz Matute (BCAM and University of Texas at Austin)'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-04-19T13:00:00Z'
date_end: 
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-01-16'

authors: [Jamie M. Taylor (CUNEF)]
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 
  focal_point: 

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---
