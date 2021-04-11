+++
title = "A Sequence-to-Sequence Traffic Predictor on Software-Defined Networking"
subtitle = "_International Journal of Web and Grid Services (IJWGS)_"
date = 2020-11-02T16:00:00
draft = false

authors = ["Yang Wenchuan", "Hua Rui", "**Zhao Qiuhan**"]

# Publication type.
# Legend:

publication_types = ["2"]

# Abstract and optional shortened version.
abstract = "Network traffic prediction is very important for load balancing and network planning. Under the current network architecture, it is difficult to realize the collection, prediction and centralized management of traffic. This paper proposes an attention-based traffic predictor (ATP) model to achieve traffic prediction in a software-defined network (SDN) environment. To improve the accuracy and efficiency of a prediction, improvements are made from three aspects: data, model, and evaluation optimization. First, during the traffic data acquisition phase, to reduce the resource consumption of the request caused by acquiring realtime network traffic information and to maintain the accuracy of the prediction, a combination of lower sampling frequency and data augmentation is adopted. Second, based on the long correlation and self-similar characteristics of network traffic, a sequence-to-sequence model with attention (Seq2Seq+Attention) is selected for network traffic prediction. Finally, the traditional mean squared error (MSE) evaluation method sets the same weight for samples of different values, which is not suitable for network traffic prediction. Therefore, this paper proposes an improved weighted MSE evaluation method. Experiments show that the proposed method can maintain the prediction accuracy while reducing the sampling frequency by 50%. The weighted MSE evaluation method can improve the accuracy by 5.37% compared with the original MSE evaluation method. On the basis of highly accurate traffic forecasts, it is possible to further realize intelligent control of network traffic, improve network utilization, reduce network delay, and improve the efficiency of intelligent services."

abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://www.inderscience.com/info/ingeneral/forthcoming.php?jcode=ijwgs"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Github Repo", url = "https://github.com/antaldaniel/eurobarometer/"}]

# Digital Object Identifier (DOI)
doi = "10.1504/IJWGS.2021.10036975"

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "TopLeft"
+++
