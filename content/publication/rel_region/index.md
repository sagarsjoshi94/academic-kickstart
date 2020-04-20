---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Relevant Region Exploration On General Cost-maps For Sampling-Based Motion Planning"
authors: [Sagar Suhas Joshi and Panagiotis Tsiotras ]
date: 2019-10-06T11:40:04-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-06T11:40:04-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Asymptotically optimal sampling-based planners require an intelligent exploration strategy to accelerate convergence. After an initial solution is found, a necessary condition for improvement is to generate new samples in the so-called Informed Set. However, Informed Sampling can be ineffective in focusing search if the chosen heuristic fails to provide a good estimate of the solution cost. This work proposes an algorithm to sample the Relevant Region instead, which is a subset of the Informed Set. The Relevant Region utilizes cost-to-come information from the planner's tree structure, reduces dependence on the heuristic, and further focuses the search. Benchmarking tests in uniform and general cost-space settings demonstrate the efficacy of Relevant Region sampling. "

# Summary. An optional shortened abstract.
summary: "An efficient exploration algorithm for planning over cost-maps. This can be applied to robots such as the Mars rover, which needs to avoid rough/danger terrains while exploration and manipulator arms, which need to perform dexterous motions."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1910.05361
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=_l9fCnSZ9rg&feature=youtu.be

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Path planning on a terrain cost-map. White areas represent the high-cost rough spaces."
  focal_point: ""
  preview_only: false

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
