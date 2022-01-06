---
title: "Adaptively Setting the Path Length for Separable Shadow Hamiltonian Hybrid Monte Carlo"
authors: 
- WilsonMongwe
- admin
- TshilidziMarwala
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2020-08-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-10-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: ""

abstract: Hybrid Monte Carlo (HMC) has been widely applied to numerous posterior inference problems in machine learning and statistics. HMC has two main practical issues, the first is the deterioration in acceptance rates as the system size increases and the second is its sensitivity to two user-specified parameters: the step size and trajectory length. The former issue is addressed by sampling from an integrator-dependent modified or shadow density and compensating for the induced bias via importance sampling. The latter issue is addressed by adaptively setting the HMC parameters, with the state-of-the-art method being the No-U-Turn Sampler (NUTS). We combine the benefits of NUTS with those attained by sampling from the shadow density, by adaptively setting the trajectory length and step size of Separable Shadow Hamiltonian Hybrid Monte Carlo (S2HMC). This leads to a new algorithm, adaptive S2HMC (A-S2HMC), that shows improved performance over S2HMC and NUTS across various targets and leaves the target density invariant.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Shadow Hamiltonian
- Seperable Shadow Hamiltonian Hybrid Monte Carlo
- No-U-Turn Sampler
- Markov Chain Monte Carlo
- Metropolis Hastings
- Hamiltonian Monte Carlo
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/document/9564021
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
