+++
# Project title.
title = "Subject Domain Extraction and Classification Model"

# Date this page was created.
date = 2017-08-10T09:00:00

# Project summary to display on homepage.
summary = "Aiming at the problem that the growing Chinese scientific and technological literature cannot be classified automatically."

# Tags: can be used for filtering projects.
tags = ["deep learning", "multi-label"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/antaldaniel"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = ""
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

## Time

From 2017-08 to 2017-12

## Project Introduction

Aiming at the problem that the growing Chinese scientific and technological literature cannot be classified automatically. Manual reading and tagging will increase labor costs, and manual methods rely too much on the professional skills of practitioners.

## Procedure
Therefore, we automatically classify the scientific and technological literature by designing the deep learning network, and the reference class is the [_CNKI_](https://www.cnki.net/). In other words, the project is an application of “Text Multi-label”. By completing the text multi-label network, we test and set different thresholds so that the distribution of scientific and technical documents is as close as possible to the original distribution, so as to improve the whole system.