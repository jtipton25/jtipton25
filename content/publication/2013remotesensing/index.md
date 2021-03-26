---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Properties of Endogenous Post-Stratified Estimation using remote sensing data"
authors: [admin, Jean Opsomer, Gretchen Moisen]
date: 2013-12-23T22:41:07-05:00
doi: "https://doi.org/10.1016/j.rse.2013.07.035"

# Schedule page publish date (NOT publication's date).
publishDate: 2017-03-23T22:41:07-05:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Post-stratification is commonly used to improve the precision of survey estimates. In traditional post-stratification methods, the stratification variable must be known at the population level. When suitable covariates are available at the population level, an alternative approach consists of fitting a model on the covariates, making predictions for the population and then stratifying on these predicted values. This method is called Endogenous Post-Stratification Estimation (EPSE) and it is well suited for applications using remote sensing data. In this article, we investigate the performance of EPSE in a realistic setting using data from the United States Forest Service Forest Inventory Analysis and Landsat Enhanced Thematic Mapper Plus. This article has three specific objectives: first, to evaluate the statistical properties of EPSE when using linear regression, spline regression, and the machine learning tool Random Forest to predict tree canopy cover using remote sensing and Geographic Information System data; second, to investigate the effect on the EPSE variance estimator using estimated stratum boundaries instead of fixed stratum boundaries; and third, to investigate the effect on the EPSE variance estimator when optimizing the stratum boundaries to minimize the variance estimate. The main findings of this article are that the EPSE variance estimator performs well using Random Forests, but can underestimate the true variance if an optimization is performed on the stratum boundaries in an attempt to minimize the variance estimate. This result supports the use of the EPSE estimator using remote sensing data in cases where there is no optimization on the variance estimator."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://projecteuclid.org/journals/annals-of-applied-statistics/volume-13/issue-4/Predicting-paleoclimate-from-compositional-data-using-multivariate-Gaussian-process-inverse/10.1214/19-AOAS1281.short
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.fs.fed.us/rm/pubs_other/rmrs_2013_tipton_j001.pdf
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
