---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      css_class: black
      background:
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
  - block: markdown
    content:
      title: "Curriculum Vitae"
      text: |
        <a href="uploads/resume.pdf" class="btn btn-primary" target="_blank">
          <img src="uploads/fr_flag.png" alt="French Flag" style="width:20px; margin-right:8px;"> Download CV in French
        </a>
        <br><br>
        <a href="uploads/resume_en.pdf" class="btn btn-primary" target="_blank">
          <img src="uploads/uk_flag.png" alt="UK Flag" style="width:20px; margin-right:8px;"> Download CV in English
        </a>
    design:
      css_class: black
      background:
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am currently working on [MobiTIC ANR project](https://anr.fr/Project-ANR-19-CE22-0010) with the aim of inferring the multimodal mobility of people in the Rhônes-Alpes region using statistical learning models and the fusion of multiple data sources.

        I try to apply/improve a range of qualitative and quantitative methods to comprehensively investigate people's mobilities.
        
        Please reach out to collaborate 😃
    design:
      css_class: black
      background:
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      css_class: black
      view: citation
  
  - block: collection
    id: news
    content:
      title: Interventions at Conferences
      subtitle: ''
      text: ''
      page_type: talk
      count: 0
      filters:
        folders:
          - talk
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      offset: 0
      order: desc
    design:
      view: article-grid
      spacing:
        padding: [0, 0, 0, 0]



---
