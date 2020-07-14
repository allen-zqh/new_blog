+++
# Project title.
title = "Frontier Science and Technology Literature Scoring and Recommendation System"

# Date this page was created.
date = 2019-11-07T09:00:00

# Project summary to display on homepage.
summary = "The project aims to solve the problem that literature viewers can't find the most suitable and high-quality article quickly."

# Tags: can be used for filtering projects.
tags = ["deep learning", "clustering algorithm"]

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

From 2019-06 to 2019-11

## Project Introduction

The project is aimed at a large number of scientific and technological literature. It’s to solve the problem that literature viewers can’t find the most suitable article quickly. For example, a NLP beginner, he doesn’t know what to read and which is a good article.

## Procedure
Through the deep learning model, This paper constructs the relationship between article content, publication time, citation number, influencing factor and score. It intends to try two trains of recommendation thought. One is the similar recommendation ranking commonly used in the field of NLP (Recommendations such as headlines, etc.). And the other is to first complete the scoring with the self-built scoring criteria, and to establish a text-to-score mapping by using the deep learning. Through the model,  it’s to get related recommendations for score ranking after scoring for the article.