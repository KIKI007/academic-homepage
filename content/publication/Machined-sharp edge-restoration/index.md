---
title: "Machined Sharp Edge Restoration For Triangle Mesh Workpiece Models Derived From Grid-Based Machining Simulation"
authors:
- admin
- Jack Szu-Shen Chen
- Jimin Joy
- Hsi-Yung Feng
date: "2019-05-27T00:00:00Z"
doi: "10.1080/16864360.2018.1462571"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-04-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: Computer-Aided Design and Applications 
publication_short: CAD&A

abstract: Grid-based machining simulation methods have become very popular due to their advantages in computational efficiency. However, these methods are prone to generating machined workpiece models with chamfer edges, which reduce model accuracy and visual quality. An effective method is presented in this paper targeting the restoration of machined edges from these chamfer edges for triangle mesh models derived from grid-based machining simulation. The method starts by detecting the chamfer edge triangles via utilizing both edge-based mesh segmentation and feature-based mesh segmentation. The outcomes of the two segmentation methods are then compared and combined to achieve improved detection accuracy. To restore the machined edges, the detected chamfer edge triangles are split by adding new points based on the neighbors of the chamfer edge triangles. Triangle quality checks are imposed during the point addition process in order to ensure that the restored edges do not negatively impact the triangle mesh quality. Once all the applicable new points are added for all the chamfer edge triangles, the edge restoration task is complete. The presented method has been implemented and executed on sample triangle mesh models derived from grid-based machining simulation. Improved edge restoration compared to that of existing edge restoration methods has been observed. Sub-second computational performance is attained for the majority of the test cases.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
url_pdf: https://www.tandfonline.com/doi/abs/10.1080/16864360.2018.1462571
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

