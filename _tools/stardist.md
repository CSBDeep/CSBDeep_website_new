---
slug: stardist
name: StarDist
title: ""
layout: toolpage-stardist
outputtype: objects
trainingdata: "Matching pairs of raw data and segmented data."
teaser: images/stardist_overview.png
---

## How to use the StarDist in Python
### Installation
Please read [this section](https://github.com/mpicbg-csbd/stardist#installation).
### Data annotation
Please read [this section](https://github.com/mpicbg-csbd/stardist#annotating-images).
### Training & prediction
Please read [this section](https://github.com/mpicbg-csbd/stardist#usage).

## How to export trained StarDist model from Python for Fiji
Call this method to export after training to export a model as a ZIP which is compatible to <a href="">running prediction in Fiji</a>:
```python
model.export_TF()
```
## How to use StarDist in Fiji
Please read [this page](https://imagej.net/StarDist).

## ![]({{ 'images/icons/credits_black.png' | relative_url }}) How to cite
Please read [this section](https://github.com/mpicbg-csbd/stardist#how-to-cite).

## ![]({{ 'images/icons/source_black.png' | relative_url }}) Source code 

{% include github_link.html url="mpicbg-csbd/stardist" text="StarDist in Python" %}
{% include github_link.html url="mpicbg-csbd/stardist-imagej" text="StarDist in Java / Fiji" %}