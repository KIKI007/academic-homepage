---
title: "CofiFab: Coarse-to-Fine Fabrication of Large 3D Objects"
authors:
- Peng Song
- Bailin Deng
- admin
- Zhichao Dong
- Wei Li
- Chi-Wing Fu
- Ligang Liu
date: "2019-05-26T00:00:00Z"
doi: "10.1145/2897824.2925876"

# Schedule page publish date (NOT publication's date).
publishDate: "2016-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: SIGGRAPH 2016
publication_short: SIGGRAPH Asia 2016

abstract: This paper presents CofiFab, a coarse-to-fine 3D fabrication solution, combining 3D printing and 2D laser cutting for cost-effective fabrication of large objects at lower cost and higher speed. Our key approach is to first build coarse internal base structures within the given 3D object using laser cutting, and then attach thin 3D-printed parts, as an external shell, onto the base to recover the fine surface details. CofiFab achieves this with three novel algorithmic components. First, we formulate an optimization model to compute fabricatable polyhedrons of maximized volume, as the geometry of the internal base. Second, we devise a new interlocking scheme to tightly connect the laser-cut parts into a strong internal base, by iteratively building a network of nonorthogonal joints and interlocking parts around polyhedral corners. Lastly, we optimize the partitioning of the external object shell into 3D-printable parts, while saving support material and avoiding overhangs. Besides cost saving, these components also consider aesthetics, stability and balancing. Hence, CofiFab can efficiently produce large objects by assembly. To evaluate CofiFab, we fabricate objects of varying shapes and sizes, and show that CofiFab can significantly outperform previous methods.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://songpenghit.github.io/Publication/projects/2016-SIGGRAPH-CofiFab/index.html
- name: SIGGRAPH 2016
url_pdf: https://songpenghit.github.io/Publication/projects/2016-SIGGRAPH-CofiFab/download/paper.highres.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://youtu.be/TXsn3BpmE0U


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Cofifab'
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

