---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Autonomous Car"
summary: "ROS Software stack for autonomous driving"
authors: []
tags: []
categories: []
date: 2019-10-09T20:42:53-04:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: "https://www.youtube.com/watch?v=BO5B2XXrntc"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
We are developing a complete ROS software stack for autonomous navigation of the MIT RACECAR robot. Please find a video of car in simulation [here](https://www.youtube.com/watch?v=u5Zc4rvt2UE). The car uses LiDAR and odometry data for SLAM. Variant of A* or a sampling-based algorithm such as RRT*, RRT# is used for path planning. 
