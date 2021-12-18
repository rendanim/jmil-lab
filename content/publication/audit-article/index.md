---
title: "Bayesian inference of local government audit outcomes"
authors: 
- WilsonMongwe
- admin
- TshilidziMarwala
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2021-12-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "PLOS ONE"
publication_short: ""

abstract: The scandals in publicly listed companies have highlighted the large losses that can result from financial statement fraud and weak corporate governance. Machine learning techniques have been applied to automatically detect financial statement fraud with great success. This work presents the first application of a Bayesian inference approach to the problem of predicting the audit outcomes of financial statements of local government entities using financial ratios. Bayesian logistic regression (BLR) with automatic relevance determination (BLR-ARD) is applied to predict audit outcomes. The benefit of using BLR-ARD, instead of BLR without ARD, is that it allows one to automatically determine which input features are the most relevant for the task at hand, which is a critical aspect to consider when designing decision support systems. This work presents the first implementation of BLR-ARD trained with Separable Shadow Hamiltonian Hybrid Monte Carlo, No-U-Turn sampler, Metropolis Adjusted Langevin Algorithm and Metropolis-Hasting algorithms. Unlike the Gibbs sampling procedure that is typically employed in sampling from ARD models, in this work we jointly sample the parameters and the hyperparameters by putting a log normal prior on the hyperparameters. The analysis also shows that the repairs and maintenance as a percentage of total assets ratio, current ratio, debt to total operating revenue, net operating surplus margin and capital cost to total operating expenditure ratio are the important features when predicting local government audit outcomes using financial ratios. These results could be of use for auditors as focusing on these ratios could potentially speed up the detection of fraudulent behaviour in municipal entities, and improve the speed and quality of the overall audit.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.

tags:
- Audit Outcomes
- Markov Chain Monte Carlo
- Metropolis Hastings
- Hamiltonian Monte Carlo
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0261245
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
