+++
title = "Detecting Heterogeneous Treatment Effect with Instrumental Variables"
date = 2017-01-01T00:00:00  # Schedule page publish date.
draft = false

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2019-05-24T11:40:00
time_end = 2019-05-24T12:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Michael Johnson"]

# Abstract and optional shortened version.
abstract = "There is an increasing interest in methods estimating heterogeneity in causal effects in randomized and observational studies. However, little research has been conducted to understand heterogeneity in an instrumental variables study. In this work, we present a method to estimate heterogeneous causal effects using an instrumental variable approach. The method has two parts. The first part uses subject-matter knowledge and interpretable machine learning techniques, such as classification and regression trees and penalized regression, to partition the data set into potential subgroups with heterogeneous treatment effects. The second part tests for heterogeneous treatment effect within these partitions. To control for the concerns of using one data set to find partitions and make statistical inference, sample-splitting and a recent method of taking the absolute value of the outcome with Bonferroni correction and closed testing are applied to strongly control for familywise error rate. We conducted this method on a real data set example on the effect of malaria on stunted child growth, which showed evidence of heterogeneity in children with and without mosquito nets for protection."
abstract_short = "Simultaneously discovering and inferring heterogeneous complier average treatment effects."

# Name of event and optional event URL.
event = "Atlantic Causal Inference Conference"
event_url = "https://www.mcgill.ca/epi-biostat-occh/news-events/atlantic-causal-inference-conference-2019"

# Location of event.
location = "Montreal, Quebec"

# Is this a selected talk? (true/false)
selected = false

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = ""
url_slides = "slides/EMIV-ACICtalk.pdf"
url_video = ""
url_code = ""

# Does the content use math formatting?
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Right"
  
#   {{% alert note %}}
# Click on the **Slides** button above to view the built-in slides feature.
# {{% /alert %}}
# 
# Slides can be added in a few ways:
# 
# - **Create** slides using Academic's *Slides* feature and link using `url_slides` parameter in the front matter of the talk file
# - **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
# - **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
# 
# Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
+++


