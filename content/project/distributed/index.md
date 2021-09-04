---
title: Distributed Estimation
summary: I studied how communication constraints affect the minimax rates in distributed estimation
tags:
- Distributed estimation
date: "2017-10-15"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Distributed estimation
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Suppose that we have data distributed across multiple computers and we wish to estimate some quantity on a central computer. Each of the computers on the network can transmit data to the central machine. We impose two constraints that make this setting much more interesting. The first is that we must transmit binary strings, so continuous data must be approximated in binary before being transmitted. The second is that we impose communication constrainits which limit the number of bits that can be transmitted. These two constraints are imposed to reflect the important real world fact that transmission across a network is slow and costly.

For parametric problems, we often have sufficient statistics that compress the data significantly. In nonparametric problems, the situation is much more interesting. The sufficient statistics are infinite dimensional, so communication constraints limit the precision of the transmitted data and the number of statistics transmitted. 


