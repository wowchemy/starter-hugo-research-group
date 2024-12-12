---
title: Can we reduce the computational burden of coagulation cascade models in cardiovascular simulations?
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
abstract: 'Thrombosis is a complex process that begins with the coagulation cascade, a series of biochemical reactions involving more than 40 species. Simulating the coagulation cascade requires solving tens of 3D unsteady advection-diffusion-reaction (ADR) equations, which is challenging. In this talk I will discuss a novel multi-fidelity approach to drastically reduce the computational burden of these simulations, leveraging the dominance of advection transport over diffusive transport in arteries to simplify the system of PDEs that represent the ADR process to a system of ODEs and a single PDE. I will present a validation test for this multi-fidelity approach in a 2D cavity with a pulsatile flow (representative of an idealized left atrial appendage or an aneurism) using a simple coagulation model with nine biochemical species. Then I will apply this methodology to patient-specific simulations of the flow in the Left Atrium. The results show that the multi-
fidelity approach is cost-effective, accurately reproducing the spatio-temporal development of the coagulation cascade. The talk will close with a discussion of further applications for this methodology in cardiovascular flows, either using CFD simulations or medical image data.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-02-16T13:00:00Z'
date_end: 
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-01-16'

authors: [Oscar Flores (Dept. Aerospace Engineering, UC3M)]
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
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
---
