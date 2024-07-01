---
title: "Computational Design of High-level Interlocking Puzzles"
authors:
- Rulin Chen
- admin
- Peng Song
- Bernd Bickel
date: "2022-08-01T00:00:00Z"
# doi: "10.1145/2897824.2925876"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal article"]

# Publication name and optional abbreviated publication name.
publication: SIGGRAPH 2022
publication_short: SIGGRAPH 2022

abstract: Interlocking puzzles are intriguing geometric games where the puzzle pieces are held together based on their geometric arrangement, preventing the puzzle from falling apart. High-level-of-difficulty, or simply high-level, interlocking puzzles are a subclass of interlocking puzzles that require multiple moves to take out the first subassembly from the puzzle. Solving a high-level interlocking puzzle is a challenging task since one has to explore many different configurations of the puzzle pieces until reaching a configuration where the first subassembly can be taken out. Designing a high-level interlocking puzzle with a user-specified level of difficulty is even harder since the puzzle pieces have to be interlocking in all the configurations before the first subassembly is taken out. In this paper, we present a computational approach to design high-level interlocking puzzles. The core idea is to represent all possible configurations of an interlocking puzzle as well as transitions among these configurations using a rooted, undirected graph called a disassembly graph and leverage this graph to find a disassembly plan that requires a minimal number of moves to take out the first subassembly from the puzzle. At the design stage, our algorithm iteratively constructs the geometry of each puzzle piece to expand the disassembly graph incrementally, aiming to achieve a user-specified level of difficulty. We show that our approach allows efficient generation of high-level interlocking puzzles of various shape complexities, including new solutions not attainable by state-of-the-art approaches.

tags:
- Source Themes
featured: true

links:
- name: Website
  url: https://sutd-cgl.github.io/supp/Publication/projects/2022-SIGGRAPH-High-LevelPuzzle/index.html
- name: SIGGRAPH 2022
url_pdf: https://sutd-cgl.github.io/supp/Publication/projects/2022-SIGGRAPH-High-LevelPuzzle/download/2022-SIGGRAPH-High-LevelPuzzle.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
url_video: https://www.youtube.com/watch?v=sl6GiL5z2OM

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'High-Level Puzzle'
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

