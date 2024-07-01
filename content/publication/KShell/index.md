---
title: "Masonry Shell Structures with Discrete Equivalence Classes
"
authors:
- Rulin Chen
- Pengyun Qiu
- Peng Song
- Bailin Deng
- admin
- Ying He
date: "2023-08-06T00:00:00Z"
#doi: "10.1145/3272127.3275034"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: SIGGRAPH 2023
publication_short: SIGGRAPH 2023

abstract: Masonry shell structures have been built for centuries around the world in the form of arches, domes and vaults, due to their advantages like large span, lightweight, and high strength. The shapes of masonry shells are generally described by 3D curved surfaces since the thickness of these structures is significantly smaller compared to its width and length. From a geometric perspective, a masonry shell is a geometric tiling of a 3D surface with a number of shell elements that contact one another with no overlaps and no gaps. To tile a freeform 3D surface, it is likely that each shell element has a unique shape when compared to the other elements, requiring each element to be custom manufactured. In this paper, we study a new problem of modeling freeform shell structures where the shell elements fall into a set of discrete equivalence classes. The major technical challenge in this process is balancing the desire for high reusability of template elements with the need for a seamless and buildable final structure. To address the challenge, we define three error metrics to measure the seamlessness and buildability of shell structures made from discrete equivalence classes and develop a hierarchical cluster-and-optimize approach to generate a small set of template elements that produce a structure closely approximating the surface with low error metrics. We demonstrate the feasibility of our approach on various freeform surfaces and geometric patterns, and validate buildability of our results with four physical results.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://sutd-cgl.github.io/supp/Publication/projects/2023-SIGGRAPH-TileableShell/index.html
- name: SIGGRAPH 2023
#url_pdf: https://sutd-cgl.github.io/supp/Publication/papers/2018-SIGAsia-DESIA.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://youtu.be/OJvWdn6Fcio


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'A masonry shell structure modeled by our approach, in which 181 shell elements fall into 60 discrete equivalence classes. Shell elements in the same class have exactly the same shape and are rendered with the same color.'
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

