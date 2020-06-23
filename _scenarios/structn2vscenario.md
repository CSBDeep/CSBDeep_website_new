---
slug: "structn2vscenario"
pretitle: "Denoising"
shorttitle: "Convallaria"
longtitle: "Denoising structured noises without clean data (Convallaria)"
inputimage: "images/n2v/struct-n2v-inpu-convallaria.jpg"
outputimage: "images/n2v/struct-n2v-output-convallaria.jpg"  
tool: n2v
inoutdata: noisy_void
---

## Authorship
The data was acquired by the LMF at Max Planck Institute for Cell Biology and Genetics and originats from this publication: [Removing Structured Noise with Self-Supervised Blind-Spot Networks](https://ieeexplore.ieee.org/document/9098336) by Coleman Broaddus et. al.

## Details
Self-supervised denoising methods may not work properly if the noise is not pixel independent and presents patterns or structures in the image. If this is the case, some methods may augment the artifacts and removing them may become complicated.
Struct Noise2Void is an extension of [Noise2Void]() that tackles the problem of denoising images which have structured and pixel-dependent noise patterns.

This example scenario shows a 2D image from _Convallaria majalis_ acquired with a Spinning Disk confocal microscope, where horizontal stripes of noise can be observed.

## Demo
A practical notebook example with python can be found [here](https://github.com/juglab/n2v/blob/master/examples/2D/structN2V_2D_synth_mem/train_and_predict.ipynb).
