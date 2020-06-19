---
slug: "denoisingU2OS"
pretitle: "Denoising"
shorttitle: "2D Human U2OS"
longtitle: "Human U2OS 2D Denoising"
inputimage: "images/care/denoising/u2os_2d_denoising_input.png"
outputimage: "images/care/denoising/u2os_2d_denoising_output.png"
inoutdata: noisy_gt
tool: care
---

## Authorship

This example is part of the [CSBDeep](https://github.com/CSBDeep/CSBDeep) framework. The method is described in [Content-aware image restoration: pushing the limits of fluorescence microscopy](http://dx.doi.org/10.1038/s41592-018-0216-7) by Martin Weigert _et al._ and the data are Human U2OS cells taken from the [Broad Bioimage Benchmark Collection](https://data.broadinstitute.org/bbbc/BBBC006/).

## Details

The low SNR images were created by synthetically adding _strong read-out and shot-noise_ (and additionally applying _pixel binning_ of 2x2) thus mimicking acquisitions at a very low light level.

## Demo

To reproduce this example follow the instructions in this [jupyter notebook](https://github.com/CSBDeep/CSBDeep/tree/master/examples/denoising2D).

