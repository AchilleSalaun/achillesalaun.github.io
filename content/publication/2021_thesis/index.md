---
title: "Alarm prediction in networks via space-time pattern matching and machine learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-07-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Thesis"]

# Publication name and optional abbreviated publication name.
#publication: "In *CNSM 2018: 14th International Conference on Network and Service Management*"
#publication_short: In *CNSM 2018*

abstract: "Nowadays, telecommunication networks occupy a predominant place in our world. Indeed, they allow to share worldwide a huge amount of information.  Networks are however complex systems, both in size and technological diversity. Therefore, it makes their management and repair more difficult. In order to limit the negative impact of such failures, some tools have to be developed to detect a failure as soons as it occurs, analyse its root causes to solve it efficiently, or even predict this failure to prevent it  rather than cure it. In this thesis, we mainly focus on these last two problems. To do so, we use files, called alarm logs, storing all the alarms issued by the system. However, these files are generally noisy and verbose: an operator managing a network needs tools able to extract and handle in an interpretable manner the causal relationships within a log. First, we build online a structure, called DIG-DAG, that stores all the potential causal relationships involving the events of a log. We then propose a query system to exploit this structure. Finally, we apply this approach in the context of root cause analysis. Second, we discuss a generative approach for times series prediction.  In particular, we compare two well-known models for this task: recurrent neural nets on the one hand, hidden Markov models on the other hand. Indeed, in their respective communities, these two models are state of the art. Here, we compare analytically their expressivity by encompassing them into a probabilistic model, called GUM."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Alarm prediction, Fault Diagnosis, Pattern Matching, Generative Models, Interpretability]

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
url_video: 'https://www.youtube.com/watch?v=_k5j1t9okRE'

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