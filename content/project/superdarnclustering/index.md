---
title: Clustering SuperDARN Backscatter Echoes
summary: Characterization of SuperDARN Backscatter Echoes using Machine Learning
tags:
- SuperDARN
- Backscatter Echoes
- Data Analytics
- Deep Learing
- Clustering
date: "2018-04-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Example output of clustering algorithm
  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: ""
#url_pdf: "https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2017RS006488"
#url_slides: ""
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: shortwavefadeout
---


This study aims to classify backscatter measured by the Super Dual Auroral Radar Network (SuperDARN) using unsupervised machine learning methods. The SuperDARN radars are used to study the ionosphere, and data from multiple radars can be combined to create ionospheric convection maps. SuperDARN backscatter can come from the ionosphere, the ground, or other sources. It is important to separate these categories cleanly so that data used for research (usually ionospheric scatter) is not contaminated by the wrong types of scatter. However, it is challenging to separate these categories because their characteristics in doppler velocity, spectral width, and other features can overlap and ground truth is rarely available. The traditional method of separating ionospheric scatter (IS) from ground scatter (GS) classifies data point by point, and misclassifies a large amount of low-velocity IS as GS to obtain clean IS data. A recent method that clusters data using a depth-first search improved on this using criteria developed specifically for conditions with low-velocity IS. However, this method uses boxcar filtering, which requires a trade-off between having the ability to find small-scale structures and contaminating the data with noise. In this study we apply unsupervised machine learning methods to cluster backscatter data, comparing Gaussian Mixture Model (GMM) and several variations on Density-Based Spatial Clustering of Applications with Noise (DBSCAN). We then classify the clusters as IS or GS using criteria from the literature. These clustering algorithms can create coherent structures in space and time separate from noise, preserve the original data, and identify more low-velocity IS, offering improvements over existing methods.
