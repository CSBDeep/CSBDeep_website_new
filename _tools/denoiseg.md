---
slug: denoiseg
name: DenoiSeg
layout: toolpage-denoiseg
outputtype: objects
trainingdata: "Noisy images, some of them with existing segmentation."
purpose: "Image restoration and object detection."
teaser: images/denoiseg/denoiseg-teaser.jpg
showoverview: true
--- 

Microscopy image analysis often requires the segmentation of objects, but training data for this task is typically scarce and hard to obtain. Here we propose DenoiSeg, a new method that can be trained end-to-end on only a few annotated ground truth segmentations. We achieve this by extending Noise2Void, a self-supervised denoising scheme that can be trained on noisy images alone, to also predict dense 3-class segmentations. The reason for the success of our method is that segmentation can profit from denoising, especially when performed jointly within the same network. The network becomes a denoising expert by seeing all available raw data, while co-learning to segment, even if only a few segmentation labels are available. This hypothesis is additionally fueled by our observation that the best segmentation results on high quality (very low noise) raw data are obtained when moderate amounts of synthetic noise are added. This renders the denoising-task non-trivial and unleashes the desired co-learning effect. We believe that DenoiSeg offers a viable way to circumvent the tremendous hunger for high quality training data and effectively enables few-shot learning of dense segmentations.

[How to use DenoiSeg in Python](https://github.com/juglab/denoiseg/){:target="_blank" class="external"}
[How to use DenoiSeg in Fiji](https://imagej.net/DenoiSeg){:target="_blank" class="external"}
[How to export trained DenoiSeg networks from Python for Fiji](){:target="_blank" class="external"}

## ![]({{ 'images/icons/source_black.png' | relative_url }}) Source code 

{% include github_link.html url="juglab/DenoiSeg" text="DenoiSeg in Python" %}
{% include github_link.html url="juglab/DenoiSeg_fiji" text="DenoiSeg in Java / Fiji" %}
