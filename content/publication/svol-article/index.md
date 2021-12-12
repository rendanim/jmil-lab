---
title: "Locally Scaled and Stochastic Volatility Metropolis– Hastings Algorithm"
authors: 
- WilsonMongwe
- admin
- TshilidziMarwala
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-12-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Alogorithms"
publication_short: ""

abstract: Markov chain Monte Carlo techniques are usually used to infer model parameters when closed-form inference is not feasible, with one of the simplest MCMC methods being the random walk Metropolis Hastings algorithm. The MH algorithm suffers from random walk behaviour, which results in inefficient exploration of the target posterior distribution. This method has been improved upon, with algorithms such as Metropolis Adjusted Langevin Monte Carlo and Hamiltonian Monte Carlo being examples of popular modifications to MH. In this work, we revisit the MH algorithm to reduce the autocorrelations in the generated samples without adding significant computational time. We present the:  Stochastic Volatility Metropolis Hastings algorithm, which is based on using a random scaling matrix in the MH algorithm, and  Locally Scaled Metropolis Hastings algorithm, in which the scaled matrix depends on the local geometry of the target distribution. For both these algorithms, the proposal distribution is still Gaussian centred at the current state. The empirical results show that these minor additions to the MH algorithm significantly improve the effective sample rates and predictive performance over the vanilla MH method. The SVMH algorithm produces similar effective sample sizes to the LSMH method, with SVMH outperforming LSMH on an execution time normalised effective sample size basis. The performance of the proposed methods is also compared to the MALA and the current state-of-art method being the No-U-Turn sampler. The analysis is performed using a simulation study based on Neal’s funnel and multivariate Gaussian distributions and using real world data modeled using jump diffusion processes and Bayesian logistic regression. Although both MALA and NUTS outperform the proposed algorithms on an effective sample size basis, the SVMH algorithm has similar or better predictive performance when compared to MALA and NUTS across the various targets. In addition, the SVMH algorithm outperforms the other MCMC algorithms on a normalised effective sample size basis on the jump diffusion processes datasets. These results indicate the overall usefulness of the proposed algorithms.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Markov Chain Monte Carlo
- Metropolis Hastings
- Stochastic Volatility
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/1384130
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
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
