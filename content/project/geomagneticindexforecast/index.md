---
title: Geomagnetic Index Forecast
summary: Forecasting geomagnetic index by machine learing / neural nets.
tags:
- Dst
- Geomagnetic Storm
- Data Analytics
- Deep Learning
date: "2020-02-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Example output from Deep-Gaussian Regression Model
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: "https://github.com/shibaji7/KpPrediction"
url_pdf: "https://www.swsc-journal.org/articles/swsc/abs/2020/01/swsc190086/swsc190086.html"
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: shortwavefadeout
---
Geomagnetic activity is often described using summary indices to summarize the likelihood of space weather impacts, as well as when parameterizing space weather models. The geomagnetic index Kp in particular, is widely used for these purposes. Current state-of-the-art forecast models provide deterministic Kp predictions using a variety of methods-including empirically-derived functions, physics-based models, and neural networks - but do not provide uncertainty estimates associated with the forecast. This paper provides a sample methodology to generate a 3-hour-ahead Kp prediction with uncertainty bounds and from this provide a probabilistic geomagnetic storm forecast. Specifically, we have used a two-layered architecture to separately predict storm (Kp > 5-) and non-storm cases. As solar wind-driven models are limited in their ability to predict the onset of transient-driven activity we also introduce a model variant using solar X-ray flux to assess whether simple models including proxies for solar activity can improve the predictions of geomagnetic storm activity with lead times longer than the L1-to-Earth propagation time. By comparing the performance of these models we show that including operationally-available information about solar irradiance enhances the ability of predictive models to capture the onset of geomagnetic storms and that this can be achieved while also enabling probabilistic forecasts.

