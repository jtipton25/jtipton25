---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Predicting paleoclimate from compositional data using multivariate Gaussian process inverse prediction"
authors: [Tipton, J.R., Mevin B. Hooten; Connor Nolan; Robert K. Booth; Jason McLachlan]
date: 2019-03-23T22:41:07-05:00
doi: "10.1214/19-AOAS1281"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-23T22:41:07-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Multivariate compositional count data arise in many applications including ecology,
  microbiology, genetics, and paleoclimate. A frequent question in the analysis of multivariate
  compositional count data is what values of a covariate(s) give rise to the observed
  composition. Learning the relationship between covariates and the compositional count allows
  for inverse prediction of unobserved covariates given compositional count observations.
  Gaussian processes provide a flexible framework for modeling functional responses with respect
  to a covariate without assuming a functional form. Many scientific disciplines use Gaussian
  process approximations to improve prediction and make inference on latent processes and
  parameters. When prediction is desired on unobserved covariates given realizations of the
  response variable, this is called inverse prediction. Because inverse prediction is
  mathematically and computationally challenging, predicting unobserved covariates often
  requires fitting models that are different from the hypothesized generative model. We present
  a novel computational framework that allows for efficient inverse prediction using a Gaussian
  process approximation to generative models. Our framework enables scientific learning about
  how the latent processes co-vary with respect to covariates while simultaneously providing
  predictions of missing covariates. The proposed framework is capable of efficiently exploring
  the high dimensional, multi-modal latent spaces that arise in the inverse problem. To
  demonstrate flexibility, we apply our method in a generalized linear model framework to
  predict latent climate states given multivariate count data. Based on cross-validation, our
  model has predictive skill competitive with current methods while simultaneously providing
  formal, statistical inference on the underlying community dynamics of the biological system
  previously not available."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://projecteuclid.org/journals/annals-of-applied-statistics/volume-13/issue-4/Predicting-paleoclimate-from-compositional-data-using-multivariate-Gaussian-process-inverse/10.1214/19-AOAS1281.short
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1903.05036
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
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
slides: ""
---
