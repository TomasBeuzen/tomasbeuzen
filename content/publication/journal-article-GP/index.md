---
title: "Ensemble models from machine learning: an example of wave runup and coastal dune erosion"
authors:
- Tomas Beuzen
- Evan Goldstein
- Kristen Splinter
date: "2019-01-01T00:00:00Z"
doi: "https://doi.org/10.5194/nhess-19-2295-2019"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-10-01T00:00:00Z" # "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Natural Hazards and Earth System Sciences, 19*"
publication_short: ""

abstract: After decades of study and significant data collection of time-varying swash on sandy beaches, there is no single deterministic prediction scheme for wave runup that eliminates prediction error – even bespoke, locally tuned predictors present scatter when compared to observations. Scatter in runup prediction is meaningful and can be used to create probabilistic predictions of runup for a given wave climate and beach slope. This contribution demonstrates this using a data-driven Gaussian process predictor; a probabilistic machine-learning technique. The runup predictor is developed using 1 year of hourly wave runup data (8328 observations) collected by a fixed lidar at Narrabeen Beach, Sydney, Australia. The Gaussian process predictor accurately predicts hourly wave runup elevation when tested on unseen data with a root-mean-squared error of 0.18 m and bias of 0.02 m. The uncertainty estimates output from the probabilistic GP predictor are then used practically in a deterministic numerical model of coastal dune erosion, which relies on a parameterization of wave runup, to generate ensemble predictions. When applied to a dataset of dune erosion caused by a storm event that impacted Narrabeen Beach in 2011, the ensemble approach reproduced ∼85 % of the observed variability in dune erosion along the 3.5 km beach and provided clear uncertainty estimates around these predictions. This work demonstrates how data-driven methods can be used with traditional deterministic models to develop ensemble predictions that provide more information and greater forecasting skill when compared to a single model using a deterministic parameterization – an idea that could be applied more generally to other numerical models of geomorphic systems.

# Summary. An optional shortened abstract.
# summary: summary goes here.

tags:
- Machine learning
- Gaussian process
- data
- runup
- erosion
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://doi.org/10.5194/nhess-19-2295-2019
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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

# Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
