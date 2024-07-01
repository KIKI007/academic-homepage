---
title: "Design and Structural Optimization of Topological Interlocking Assemblies"
authors:
- admin
- Peng Song
- Florin Isvoranu
- Mark Pauly
date: "2019-09-11T00:00:00Z"
doi: "10.1145/3355089.3356489"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-09-11T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: SIGGRAPH Asia 2019
publication_short: SIGGRAPH Asia 2019

abstract: "We study assemblies of convex rigid blocks regularly arranged to approximate a given freeform surface. Our designs rely solely on the geometric arrangement of blocks to form a stable assembly, neither requiring explicit connectors or complex joints, nor relying on friction between blocks. The convexity of the blocks simplifies fabrication, as they can be easily cut from different materials such as stone, wood, or foam. However, designing stable assemblies is challenging, since adjacent pairs of blocks are restricted in their relative motion only in the direction orthogonal to a single common planar interface surface. We show that despite this weak interaction, structurally stable, and in some cases, globally interlocking assemblies can be found for a variety of freeform designs. Our optimization algorithm is based on a theoretical link between static equilibrium conditions and a geometric, global interlocking property of the assembly-that an assembly is globally interlocking if and only if the equilibrium conditions are satisfied for arbitrary external forces and torques. Inspired by this connection, we define a measure of stability that spans from single-load equilibrium to global interlocking, motivated by tilt analysis experiments used in structural engineering. We use this measure to optimize the geometry of blocks to achieve a static equilibrium for a maximal cone of directions, as opposed to considering only self-load scenarios with a single gravity direction. In the limit, this optimization can achieve globally interlocking structures. We show how different geometric patterns give rise to a variety of design options and validate our results with physical prototypes."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
#- name: Website
  #url: https://lgg.epfl.ch/publications/2019/Topological_Interlocking/index.php
- name: SIGGRAPH AISA 2019
url_pdf: https://sutd-cgl.github.io/supp/Publication/papers/2019-SIGAsia-TopoInterlock.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://youtu.be/EUm6IIdk2XM


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Roof'
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

