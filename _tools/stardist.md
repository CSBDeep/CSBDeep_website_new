---
slug: stardist
name: StarDist
title: ""
layout: toolpage-stardist
outputtype: objects
trainingdata: "Matching pairs of raw data and segmented data."
purpose: "Object detection."
teaser: images/stardist_overview.png
---

Automatic detection and segmentation of cells and nuclei in microscopy images is important for many biological applications. Recent successful learning-based approaches include per-pixel cell segmentation with subsequent pixel grouping, or localization of bounding boxes with subsequent shape refinement. In situations of crowded cells, these can be prone to segmentation errors, such as falsely merging bordering cells or suppressing valid cell instances due to the poor approximation with bounding boxes. To overcome these issues, we propose to localize cell nuclei via star-convex polygons, which are a much better shape representation as compared to bounding boxes and thus do not need shape refinement. To that end, we train a convolutional neural network that predicts for every pixel a polygon for the cell instance at that position. We demonstrate the merits of our approach on two synthetic datasets and one challenging dataset of diverse fluorescence microscopy images.

[How to use StarDist in Python](https://github.com/mpicbg-csbd/stardist){:target="_blank" class="external"}
[How to use StarDist in Fiji](https://imagej.net/StarDist){:target="_blank" class="external"}
[How to cite StarDist](https://github.com/mpicbg-csbd/stardist#how-to-cite){:target="_blank" class="external"}

## ![]({{ 'images/icons/source_black.png' | relative_url }}) Source code 

{% include github_link.html url="mpicbg-csbd/stardist" text="StarDist in Python" %}
{% include github_link.html url="mpicbg-csbd/stardist-imagej" text="StarDist in Java / Fiji" %}


