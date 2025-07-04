---
title: "DIG-DAG: stockage et recherche de motifs dans un flux d'événements"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- anne
- marco
- admin
- maxime

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-10-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Conference"]

# Publication name and optional abbreviated publication name.
publication: "In *ALGOTEL 2020: 22èmes Rencontres Francophones sur les Aspects Algorithmiques des Télécommunications*"
publication_short: In *ALGOTEL*

abstract: "La recherche de motifs dans une chaîne de caractères se réalise facilement avec un outil tel que grep. Dans cet article, nous considérons un flux d’événements caractérisés par une date de début et de fin. La recherche de motifs dans une telle structure devient alors plus complexe. Afin de réaliser efficacement cette opération, nous proposons une nouvelle structure, appelée DIG-DAG (Directed Interval Graph - Directed Acyclic Graph). Nous montrons comment construire de manière compacte cette structure lorsque le flux est découvert à la volée. Nous expliquons ensuite comment extraire du DIG-DAG les motifs conformes à la requête d’un utilisateur. Enfin, nous illustrons l’utilisation de ces algorithmes sur des traces réelles issues de réseaux GSM. Cet article synthétise deux articles publiés dans [CNSM’2018](https://achillesalaun.github.io/publication/2018_cnsm/) et [MLN’2019](https://achillesalaun.github.io/publication/2019_mln/)."

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
