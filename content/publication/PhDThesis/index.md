---
title: "Computational Analysis and Design of Structurally Stable Assemblies with Rigid Parts"
date: "2021-12-28T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-12-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Thesis"]

# Publication name and optional abbreviated publication name.
publication: EPFL Thesis
publication_short: Thesis

abstract: An assembly refers to a collection of parts joined together to achieve a specific form and/or functionality. Assemblies make it possible to fabricate large and complex objects with several small and simple parts. Such parts can be assembled and disassembled repeatedly, benefiting the transportation and maintenance of the assembly. Due to these advantages, assemblies are ubiquitous in our daily lives, including most furniture, household appliances, and architecture. The recent advancement in digital fabrication lowers the hurdles for fabricating objects with complex shapes. However, designing physically plausible assemblies is still a non-trivial task as a slight local modification on a part's geometry could have a global impact on the structural and/or functional performance of the whole assembly. New computational tools are developed to enable general users involved in the design process exploiting their imagination. This thesis focuses on static assemblies with rigid parts. We develop computational methods for analyzing and designing assemblies that are structurally stable and assemblable. To address this problem, we use integral joints i.e., tenon and mortise, that are historically used because of their reversibility which simplifies the disassembly process significantly. Properly arranged integral joints can restrict parts' relative movement for improved structural stability. However, manually finding the right joints' geometry is a tedious and error-prone task. Inspired by the kinematic-static duality, we first propose a new kinematic-based method for analyzing the structural stability of assemblies. We then develop a two-stage computational design framework based on this new analyzing method. The kinematic design stage determines the amount of motion restrictions imposed by joints to make a given assembly stable in the motion space. The geometric design stage searches for proper shapes of the joints to satisfy the motion restriction requirements computed from the previous stage. To solve the problem numerically, we propose the joint motion cones to measure the motion restriction capacity of given joints. Compared with previous works, our framework can efficiently handle inputs with complex geometry. Besides, our design framework is very flexible and can easily be adapted to various applications. First, we focus on designing globally interlocking assemblies that can withstand arbitrary external forces and torques. Second, we are interested in designing assemblies of rigid convex blocks to approximate freeform surfaces. Our design framework can optimize the blocks' shape to generate assemblies with good resistance against lateral forces, and in some cases, globally interlocking assemblies. Lastly, we present a method for designing complex assemblies with cone joints. By optimizing the shapes of cone joints, our design framework can find the best trade-off between structural stability and assemblability. We validate our computational tools by fabricating a series of physical prototypes. Our algorithms have great potential to be applied for solving various assembly design problems ranging from small-scale such as toys and furniture to large-scale such as art installation and architecture. For example, the proposed techniques could be applied for designing discrete architecture that can be automatically constructed with robots.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: PhD Thesis
  url: https://infoscience.epfl.ch/record/290668
# url_video: https://youtu.be/TXsn3BpmE0U


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
  # caption: 'Cofifab'
  # focal_point: Smart
  # preview_only: true

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

