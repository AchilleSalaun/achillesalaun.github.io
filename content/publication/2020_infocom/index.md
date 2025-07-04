---
title: "Demo abstract: end-to-end root cause analysis of a mobile network"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- anne
- marco

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-07-09T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Conference"]

# Publication name and optional abbreviated publication name.
publication: "In *INFOCOM 2020: IEEE International Conference on Computer Communications*"
publication_short: In *INFOCOM*

abstract: "In telecommunications, fault management is critical to improve network availability and user experience. To enhance reliability of their networks, operators require tools to quickly understand the cause of an outage. In particular, logs of alarms keep track of failures arising in their infrastructures. Due to the increasing size of networks and to the high diversity of technologies, these files may be verbose and noisy. That is why analyzing a log is often complex, hence delaying recovery and then degrading network availability. This demo presents a tool suite dedicated to log analysis. Our methodology is illustrated through the processing of a real alarm log issued from a 4G network. First, one can simplify the log by discarding irrelevant alarms and by clustering co-occurrent ones. Then, the underlying graph structure, called DIG-DAG, can store causal patterns by processing the input log online. Hence, experts can query the DIG-DAG to retrieve small and interpretable patterns."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Online Algorithm, Pattern Matching, Fault Diagnosis]

# Display this page in the Featured widget?
featured: false

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
url_video: 'https://www.youtube.com/watch?v=lCMQLsoLCoY'

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
