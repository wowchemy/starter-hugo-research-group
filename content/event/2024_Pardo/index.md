---
title: Variational Physics-Informed Neural Networks Optimized with Least Squares and Adaptivity in the Test Space
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
abstract: 'In practical scenarios, Robust Variational Physics-Informed Neural Networks
RVPINNs [2] face significant challenges often related to the erratic convergence of the 
Stochastic Gradient Descent-based optimizers, like Adam. However, an interesting perspective
emerges when interpreting the neurons in the last hidden layer of the NN as a basis of the 
discrete trial space. By doing so, one may boost the perfomance of the optimizer by introducing
a least-squares (LS) solver to determine the trainable parameters of the last hidden layer (Cyr
et al., [1]).\

In the first part of this talk, we discuss the implications of using a hybrid GD/LS solver.
In particular, using the discrete weak formulation involves calculating spatial derivatives for
functions within the trial space’s spanning set. Therefore, the computational cost of each
training iteration may vary based on the chosen automatic differentiation strategy for these
calculations. On the other hand, it is possible to adopt an ultraweak variational formulation
of the PDE, by transferring derivatives from the trial to the test space through repeated
integration by parts, assuming suitable regularity in the user-selected test functions. In this
scenario, assembling the LS system does not require automatic differentiation of the NN model,
leading to improved performance speeds.\

In the second part of this talk, we delve into a specific case of RVPINNs known as the Deep
Fourier Residual (DFR) method, introduced in [3, 4]. In this method, the loss is equivalent
to the dual norm of the error. Moreover, there the calculation of the dual norm relies on the
spectrum of the test function space. This representation is well-known only for rectangles in
2D or rectangular cuboids in 3D. Here, we present an extension of the DFR method utilizing
adaptive strategies on general polygonal domains. We decompose the PDE domain $\Omega$ into
overlapping rectangular subdomains, and propose a loss function that is computed as the sum
of local loss functions. Employing a Döfler marking algorithm allows us to adaptively refine the
initial subdomain decomposition of $\Omega$, enhancing the accuracy of the approximated solution
in relevant regions of the domain--essentially, we integrate adaptivity into the test space and
mantain the equivalence between the loss and the actual error of the NN aproximate solution.\

To demonstrate the effectiveness of the ultraweak implementation of the DFR loss function
equipped with a hybrid Adam/LS solver, we provide numerical examples in 1D and 2D. Our
results show dramatic improvements in both convergence speed and computational cost, 
surpassing the performance of Adam or Adam/LS with weak-type implementations. Furthermore,
our numerical experiments reveal the generation of quasi-optimal refined meshes in several 1D
and 2D problems, including the singular L-shape domain problem.

#### References:

* [1] *E.C. Cyr, et al. Robust training and initialization of deep neural networks: An adaptive basis viewpoint.
Mathematical and Scientific Machine Learning, pp. 512-536. PMLR, 2020.*

* [2] *Rojas, S., Maczuga, P., Muñoz-Matute, J., Pardo, D., and Paszynski, M. Robust Variational Physics-
Informed Neural Networks. arXiv preprint arXiv:2308.16910, 2023*

* [3] *J.M. Taylor, D. Pardo and I. Muga. A Deep Fourier Residual method for solving PDEs using Neural
Networks. Computer Methods in Applied Mechanics and Engineering, vol. 405, p. 115850, 2023.*

* [4] *J.M. Taylor, M. Bastidas, D. Pardo and I. Muga Deep Fourier Residual method for solving time-harmonic
Maxwell’s equations. arXiv preprint : arXiv:2305.09578, 2023.*'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2024-03-01T13:00:00Z'
date_end: 
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2023-01-16'

authors: [David Pardo (Ikerbasque, UPV/EHU, BCAM)]
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
