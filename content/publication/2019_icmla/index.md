---
title: "Comparing the modeling powers of RNN and HMM"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- yohan
- francois

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2019-12-18T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Conference"]

# Publication name and optional abbreviated publication name.
publication: "In *ICMLA 2019: 18th International Conference on Machine Learning and Applications*"
publication_short: In *ICMLA*

abstract: "Recurrent Neural Networks (RNN) and Hidden Markov Models (HMM) are popular models for processing sequential data and have found many applications such as speech recognition, time series prediction or machine translation. Although both models have been extended in several ways (eg. Long Short Term Memory and Gated Recurrent Unit architec-tures, Variational RNN, partially observed Markov models.. .), their theoretical understanding remains partially open. In this context, our approach consists in classifying both models from an information geometry point of view. More precisely, both models can be used for modeling the distribution of a sequence of random observations from a set of latent variables; however, in RNN, the latent variable is deterministically deduced from the current observation and the previous latent variable, while, in HMM, the set of (random) latent variables is a Markov chain. In this paper, we first embed these two generative models into a generative unified model (GUM). We next consider the subclass of GUM models which yield a stationary Gaussian observations probability distribution function (pdf). Such pdf are characterized by their covariance sequence; we show that the GUM model can produce any stationary Gaussian distribution with geometrical covariance structure. We finally discuss about the modeling power of the HMM and RNN submodels, via their associated observations pdf: some observations pdf can be modeled by a RNN, but not by an HMM, and vice versa; some can be produced by both structures, up to a re-parameterization."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Generative Models, Hidden Markov Models, Recurrent Neural Networks]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  # focal_point: ""
  # preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
#---
#
#{{% callout note %}}
#Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}
#
#{{% callout note %}}
#Create your slides in Markdown - click the *Slides* button to check out the example.
#{{% /callout %}}
#
#Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
---
