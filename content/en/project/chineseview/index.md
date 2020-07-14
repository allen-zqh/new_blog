+++
# Project title.
title = "Chinese Internet Text View Extraction Management Software"

# Date this page was created.
date = 2017-07-15T09:00:00

# Project summary to display on homepage.
summary = "Designing a software to help the goverment quickly know appeals from the public."

# Tags: can be used for filtering projects.
tags = ["extraction summarization", "recommendation"]

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

## Project Introduction

The project is the first project to cooperate with the Intelligence Institute (BISTI) after I enter the laboratory.
It aims to simplify one or a batch of Internet news content for users and sends a message in one sentence.

## Procedure
By crawling a large number of Internet text files and data cleaning, pretreatment, word vector conversion and other operations, it’s to extract the core viewpoints of Internet text. In other words, it is an application of “automatic text summary”. The comparison is performed in two ways. The one is the design of word frequency abstract algorithm based on traditional machine learning (e.g. textrank, etc.). The second is based on in-depth learning seq2seq. Through this project, I am familiar with some background knowledge and related research in my field, and follow up several development directions and frontier algorithms in the field of NLP. 