---
slug: "denoisingplanaria"
pretitle: "Denoising"
shorttitle: "Denoising in 3D"
longtitle: "Denoising in 3D (Planaria nuclei)"
inputimage: "images/care/denoising/denoising_planaria_magma_input.png"
outputimage: "images/care/denoising/denoising_planaria_magma_network.png"
inoutdata: noisy_gt
videos:
  - url: "00JSI37yrSQ"
    description: "Enabling live-cell imaging of the flatworm *S. mediterranea*."  
  - url: "a_5OegJZiaE"
    description: "Denoising results on an entire multi-tiled *S. mediterranea* samples."  
tool: care
---

## Authorship

This work (method and data) is part of [Content-aware image restoration: pushing the limits of fluorescence microscopy](http://dx.doi.org/10.1038/s41592-018-0216-7) by Martin Weigert et al. in Nature Methods. 

## Details

Input and reconstructions of a trained CARE Network on previously unseen live imaging data of *Schmidtea mediterranea*.

We consistently observed that the reconstructed image data was of very high quality, even if the signal to noise ratio (SNR) of the input was very low, e.g. being acquired with a 60-fold reduced light-dosage.

## Demo

The trained model is published for demonstration purposes. You can try it via Fiji and KNIME.

To run the demo in Fiji, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/Fiji-Command-%E2%80%93-3D-Denoising-(Planaria)).

To run the demo in KNIME, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/KNIME-Workflow-%E2%80%93-3D-Denoising-(Planaria)).

