---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Reconstruction of spatio-temporal temperature from sparse historical records using robust probabilistic principal component regression"
authors: ["**admin**", Mevin B. Hooten, Simon Goring]
date: 2017-01-27T22:41:07-05:00
doi: "https://doi.org/10.5194/ascmo-3-1-2017"

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

abstract: "Scientific records of temperature and precipitation have been kept for several hundred years, but for many areas, only a shorter record exists. To understand climate change, there is a need for rigorous statistical reconstructions of the paleoclimate using proxy data. Paleoclimate proxy data are often sparse, noisy, indirect measurements of the climate process of interest, making each proxy uniquely challenging to model statistically. We reconstruct spatially explicit temperature surfaces from sparse and noisy measurements recorded at historical United States military forts and other observer stations from 1820 to 1894. One common method for reconstructing the paleoclimate from proxy data is principal component regression (PCR). With PCR, one learns a statistical relationship between the paleoclimate proxy data and a set of climate observations that are used as patterns for potential reconstruction scenarios. We explore PCR in a Bayesian hierarchical framework, extending classical PCR in a variety of ways. First, we model the latent principal components probabilistically, accounting for measurement error in the observational data. Next, we extend our method to better accommodate outliers that occur in the proxy data. Finally, we explore alternatives to the truncation of lower-order principal components using different regularization techniques. One fundamental challenge in paleoclimate reconstruction efforts is the lack of out-of-sample data for predictive validation. Cross-validation is of potential value, but is computationally expensive and potentially sensitive to outliers in sparse data scenarios. To overcome the limitations that a lack of out-of-sample records presents, we test our methods using a simulation study, applying proper scoring rules including a computationally efficient approximation to leave-one-out cross-validation using the log score to validate model performance. The result of our analysis is a spatially explicit reconstruction of spatio-temporal temperature from a very sparse historical record."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: 
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ascmo.copernicus.org/articles/3/1/2017/ascmo-3-1-2017.pdf
url_code: https://github.com/jtipton25/observer
url_dataset: https://github.com/jtipton25/observer
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
