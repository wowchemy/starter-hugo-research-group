---
title: Ion temperature gradient turbulence numerical calculations

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- J.D. Alvarez
- L. Garcia

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '1999-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-12T12:22:37.229232Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- article-journal

# Publication name and optional abbreviated publication name.
publication: '*Computer Physics Communications*'
publication_short: ''

doi: 10.1016/s0010-4655(06)70004-2

abstract: 'Ion temperature gradient (ITG) turbulence, also referred as ηi-mode, has
  been proposed as one of the dominant mechanisms determining the transport properties
  in the core of magnetic fusion devices such as tokamaks. In this work we intend
  to study the saturated ITG turbulence using a non-linear fluid description of the
  plasma including time evolution equations for perturbed ion density, parallel velocity
  and temperature in cylindrical-toroidal geometry. This problem has been treated
  numerically developing a parallel code to run in a Masivelly Parallel Machine with
  distributed memory, like CRAY-T3E. Finite differences in radius and Fourier mode
  expansion in poloidal and toroidal angles have been used. The numerical scheme is
  time implicit for linear terms and time explicit for nonlinear term. These nonlinear
  terms are quadratic nonlinearities that become convolutions of the Fourier components.
  The implicit linear term is solved with inversion of block tridiagonal matrices.
  To numerically advance these equations, a two-step, second-order accurate, time-centered
  advancement scheme is used. The serial code runs on all processors in a synchronous
  way, each processor works over a part of the problem. The distribution of calculations
  is: in harmonic Fourier to solve the implicit part (mainly invert matrices), and
  in radial points for the explicit calculations (mainly convolutions). In each time
  step, all processors must know the results obtained with the rest. To make this,
  the PVM (Parallel Virtual Machine) routines have been used to send and receive the
  data between processors.'

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
    https://www.scopus.com/inward/record.uri?eid=2-s2.0-0033185512&doi=10.1016%2fs0010-4655%2806%2970004-2&partnerID=40&md5=59f10fd8e3bdfe5a88dff4358f736327
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
