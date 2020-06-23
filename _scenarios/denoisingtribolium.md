---
slug: "astronomy"
pretitle: "Denoising"
shorttitle: "Denoising in 3D"
longtitle: "Denoising in 3D (Tribolium nuclei)"
inputimage: "images/care/denoising/denoising_tribolium_magma_input.png"
outputimage: "images/care/denoising/denoising_tribolium_magma_network.png"
tool: care
inoutdata: noisy_gt
videos:
  - url: "oawqymyaaLw"
    description: "Denoising results on a developing *T. castaneum* (red flour beetle) embryo."  
---

## Authorship

This work (method and data) is part of [Content-aware image restoration: pushing the limits of fluorescence microscopy](http://dx.doi.org/10.1038/s41592-018-0216-7) by Martin Weigert et al. in Nature Methods. 

## Details

Live-cell imaging of developing *Tribolium castaneum* (red flour beetle) embryos. We employed the same training strategy as for the previous example. Please note that the shown result is performed in full 3D, but only one 2D image slice is shown.

We observe high quality reconstructions even on extremely noisy input data with up to 70-fold reduced light-dosage when compared to typical imaging protocols.

## Demo

The trained model is published for demonstration purposes. You can try it via Fiji and KNIME.

To run the demo in Fiji, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/Fiji-Command-%E2%80%93-3D-Denoising-(Tribolium)).

To run the demo in KNIME, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/KNIME-Workflow-%E2%80%93-3D-Denoising-(Tribolium)).

