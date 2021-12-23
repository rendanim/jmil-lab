---
title: "Separable Shadow Hamiltonian Hybrid Monte Carlo for Bayesian Neural Network Inference in wind speed forecasting"
authors: 
- admin
- WilsonMongwe
- TshilidziMarwala
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Energy and AI"
publication_short: ""

abstract: Accurate wind speed and consequently wind power forecasts form a critical enabling tool for large scale wind energy adoption. Probabilistic machine learning models such as Bayesian Neural Network (BNN) models are often preferred in the forecasting task as they facilitate estimates of predictive uncertainty and automatic relevance determination (ARD). Hybrid Monte Carlo (HMC) is widely used to perform asymptotically exact inference of the network parameters. A significant limitation to the increased adoption of HMC in inference for large scale machine learning systems is the exponential degradation of the acceptance rates and the corresponding effective sample sizes with increasing model dimensionality due to numerical integration errors. This paper presents a solution to this problem by sampling from a modified or shadow Hamiltonian that is conserved to a higher-order by the leapfrog integrator. BNNs trained using Separable Shadow Hamiltonian Hybrid Monte Carlo (S2HMC) are used to forecast one hour ahead wind speeds on the Wind Atlas for South Africa (WASA) datasets. Experimental results find that S2HMC yields higher effective sample sizes than the competing HMC. The predictive performance of S2HMC and HMC based BNNs is found to be similar. We further perform hierarchical inference for BNN parameters by combining the S2HMC sampler with Gibbs sampling of hyperparameters for relevance determination. A generalisable ARD committee framework is introduced to synthesise the various sampler ARD outputs into robust feature selections. Experimental results show that this ARD committee approach selects features of high predictive information value. Further, the results show that dimensionality reduction performed through this approach improves the sampling performance of samplers that suffer from random walk behaviour such as Metropolis–Hastings (MH).

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Bayesian Neural Networks
- Markov Chain Monte Carlo
- Separable HamiltonianShadow Hybrid Monte Carlo
- Automatic Relevance Determination
- Wind speed
- Wind power
- Forecasting
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S2666546821000586
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

#Supplementary notes can be added here, including #[code and #math]#(https://sourcethemes.com/academic/docs/writing-markdown-latex/).
