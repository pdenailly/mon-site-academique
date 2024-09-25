---
title: "Deep probabilistic forecasting of count data in multimodal transport systems"
authors:
#- admin
- Paul de Nailly, Etienne Côme, Latifa Oukhellou, Allou Samé, Jacques Ferrière
author_notes:
- "Equal contribution"
- "Equal contribution"
#date: "2024-09-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-23T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*Second Triennial Transportation and Logistics Society Conference (TSL 2023)*"
publication_short: ""

#abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://hal.science/hal-04496090/
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

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
slides: example
---

Predicting pedestrian flows in transportation areas is a major research topic that can be used to enrich passenger information for public transport passengers, who may thus better plan their trips. It can also be used by transport operators to regulate transport supply with regards to demand. Much of the work on user demand prediction focus on average predictions, and therefore cannot be used for uncertainty analysis.
However, this uncertainty is particularly appropriate in the transportation domain, where the risk of poorly managed high demand is to be avoided.
We propose the implementation of probabilistic prediction models of passenger flows in a major multimodal transportation hub with methods based on deep learning. These models are able to model uncertainty by relying on an abstraction of contextual data and by assuming output distributions.
We implement a new probabilistic prediction model based on deep learning, adding to the literature associated with these models. Our model learns a latent representation of the input data with the help of a recurrent neural network, and then translates it into multi-point passenger flow predictions with a "sum and shares" distribution, encountered in the literature.
We compare this model with others from the state of the art, using open source data and data on the La Défense hub case study. Our model seems to better perform in specific situations where data present regularities.

<iframe src="https://drive.google.com/file/d/13bnIjhrBGK7wqkcwWuqihAbVG8BfL_3t/preview" width="100%" height="600px"></iframe>