---
slug: care
layout: toolpage-care
showoverview: true
title: ""
name: CARE
trainingdata: "Matching image pairs."
purpose: "Image restoration."
outputtype: image
teaser: images/csbdeep-teaser.jpg
---

Fluorescence microscopy is a key driver of discoveries in the life-sciences, with observable phenomena being limited by the optics of the microscope, the chemistry of the fluorophores, and the maximum photon exposure tolerated by the sample. These limits necessitate trade-offs between imaging speed, spatial resolution, light exposure, and imaging depth. In this work we show how deep learning enables biological observations beyond the physical limitations of microscopes. On seven concrete examples we illustrate how microscopy images can be restored even if 60-fold fewer photons are used during acquisition, how isotropic resolution can be achieved even with a 10-fold under-sampling along the axial direction, and how diffraction-limited structures can be resolved at 20-times higher frame-rates compared to state-of-the-art methods. All developed image restoration methods are freely available as open source software.

[CARE networks documentation](https://csbdeep.bioimagecomputing.com/doc/){:target="_blank" class="external"}
[How to use the CARE networks in Python](https://github.com/CSBDeep/CSBDeep/tree/master/examples){:target="_blank" class="external"}
[How to export trained CARE networks from Python for Fiji and KNIME](https://github.com/CSBDeep/CSBDeep_website/wiki/Your-Model-in-Fiji){:target="_blank" class="external"}
[How to use the CARE networks in Fiji](https://github.com/CSBDeep/CSBDeep_website/wiki/CSBDeep-in-Fiji){:target="_blank" class="external"}
[How to use the CARE networks in KNIME](https://github.com/CSBDeep/CSBDeep_website/wiki/CSBDeep-in-KNIME){:target="_blank" class="external"}

## Setup and Exercises

 * [Setup instructions](https://csbdeep.bioimagecomputing.com/exercises/Setup_CARE.pdf) to create a python training environment for CARE.
 * [Exercise sheet](https://csbdeep.bioimagecomputing.com/exercises/Exercises_CARE.pdf) on how to train a CARE network (supervised and Noise2Noise).

## ![]({{ 'images/icons/source_black.png' | relative_url }}) Source code 

{% include github_link.html url="CSBDeep/CSBDeep" text="CSBDeep in Python" %}
{% include github_link.html url="CSBDeep/CSBDeep_fiji" text="CSBDeep in Java / Fiji" %}
