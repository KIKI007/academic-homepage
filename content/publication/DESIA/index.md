---
title: "DESIA: A General Framework for Designing Interlocking Assemblies"
authors:
- admin
- Peng Song
- Mark Pauly
date: "2019-05-28T00:00:00Z"
doi: "10.1145/3272127.3275034"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: SIGGRAPH Asia 2018
publication_short: SIGGRAPH Asia 2018

abstract: Interlocking assemblies have a long history in the design of puzzles, furniture, architecture, and other complex geometric structures. The key defining property of interlocking assemblies is that all component parts are immobilized by their geometric arrangement, preventing the assembly from falling apart. Computer graphics research has recently contributed design tools that allow creating new interlocking assemblies. However, these tools focus on specific kinds of assemblies and explore only a limited space of interlocking configurations, which restricts their applicability for design. <br> In this paper, we propose a new general framework for designing interlocking assemblies. The core idea is to represent part relationships with a family of base Directional Blocking Graphs and leverage efficient graph analysis tools to compute an interlocking arrangement of parts. This avoids the exponential complexity of brute-force search. Our algorithm iteratively constructs the geometry of assembly components, taking advantage of all existing blocking relations for constructing successive parts. As a result, our approach supports a wider range of assembly forms compared to previous methods and provides significantly more design flexibility. We show that our framework facilitates efficient design of complex interlocking assemblies, including new solutions that cannot be achieved by state of the art approaches.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Website
  #url: https://lgg.epfl.ch/publications/2018/DESIA/index.php
- name: SIGGRAPH AISA 2018
url_pdf: https://sutd-cgl.github.io/supp/Publication/papers/2018-SIGAsia-DESIA.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://youtu.be/Pqwo3GbxBEo


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'DESIA'
  focal_point: Smart
  preview_only: true

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

