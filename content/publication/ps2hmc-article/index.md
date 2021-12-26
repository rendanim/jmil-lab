---
title: "Utilising Partial Momentum Refreshment in Separable Shadow Hamiltonian Hybrid Monte Carlo"
authors:
- WilsonMongwe
- admin
- TshilidziMarwala
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-11-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: ""

abstract: Sampling using integrator-dependent shadow Hamiltonian’s has been shown to produce improved sampling properties relative to Hamiltonian Monte Carlo. The shadow Hamiltonian’s are typically non-separable, requiring the expensive generation of momenta, with the recent trend being to utilise partial momentum refreshment. Separable Shadow Hamiltonian Hybrid Monte Carlo (S2HMC) employs a canonical transformation which results in the Hamiltonian being separable and makes use of a processed leapfrog integrator. In this work, we combine the benefit of sampling using S2HMC with partial momentum refreshment to create the Separable Shadow Hamiltonian Hybrid Monte Carlo with Partial Momentum Refreshment (PS2HMC) algorithm which leaves the target distribution invariant. Numerical experiments across various targets show that the proposed algorithm outperforms S2HMC and Shadow Hamiltonian Monte Carlo with partial momentum refreshment. Comprehensive analysis is performed on the Banana shaped distribution, multivariate Gaussian distributions of various dimensions, Bayesian logistic regression and Bayesian neural networks

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Partial Momentum Refreshment
- Bayesian Neural Networks
- Markov Chain Monte Carlo
- Separable Hamiltonian
- Shadow Hybrid Monte Carlo
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/abstract/document/9610024
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

