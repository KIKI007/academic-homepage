---
title: "A Temporal Coherent Topology Optimization Approach for Assembly
Planning of Bespoke Frame Structures"
authors:
- admin
- Florian Kennel-Maushart
- Yijiang Huang
- Bernhard Thomaszewski
- Stelian Coros
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

abstract: We present a computational framework for planning the assembly sequence of bespoke frame structures. Frame structures are one of the most commonly used structural systems in modern architecture, providing resistance to gravitational and external loads. Building frame structures requires traversing through several partially built states. If the assembly sequence is planned poorly, these partial assemblies can exhibit substantial deformation due to self-weight, slowing down or jeopardizing the assembly process. Finding a good assembly sequence that minimizes intermediate deformations is an interesting yet challenging combinatorial problem that is usually solved by heuristic search algorithms. In this paper, we propose a new optimization-based approach that models sequence planning using a series of topology optimization problems. Our key insight is that enforcing temporal coherent constraints in the topology optimization can lead to sub-structures with small deformations while staying consistent with each other to form an assembly sequence. We benchmark our algorithm on a large data set and show improvements in both performance and computational time over greedy search algorithms. In addition, we demonstrate that our algorithm can be extended to handle assembly with static or dynamic supports. We further validate our approach by generating a series of results in multiple scales, including a real-world prototype with a mixed reality assistant using our computed sequence and a simulated example demonstrating a multi-robot assembly application.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: paper
  url: publication/temporalcoherenttopologyoptimization/paper.pdf
- name: supplementary
  url: publication/temporalcoherenttopologyoptimization/suppl.pdf
- name: SIGGRAPH 2023
  url: 
- name: Video
  url: https://youtu.be/VTFGXlluv04
- name: AR/Robot Video
  url: https://youtu.be/HRmducDM7ws

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Temporal Coherent Topology Optimization.'
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

