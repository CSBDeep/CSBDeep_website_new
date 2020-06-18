---
slug: "isonetretina"
pretitle: "Isonet"
shorttitle: "Retina"
longtitle: "Retina Isotropic Reconstruction"
inputimage: "images/care/isonet/isonet_retina_input.png"
outputimage: "images/care/isonet/isonet_retina_network.png"
tool: care
inoutdata: noisy_gt
videos:
  - url: "MzMJxApA7IQ"
    description: "Using CARE to computationally increase axial resolution of an imaged zebrafish retina to de-facto isometric resolution."  
---

## Authorship

This work (method and data) is part of [Content-aware image restoration: pushing the limits of fluorescence microscopy](http://dx.doi.org/10.1038/s41592-018-0216-7) by Martin Weigert et al. in Nature Methods. 

## Details

In contrast to previous examples, isotropic volumes that could be used as input/ground-truth training pairs are not readily obtainable. Therefore we propose to compute realistic observations from real ground-truth image data *in-silico*.

We applied this approach to 10-fold undersampled acquisitions of the developing retina of *Danio rerio* (zebrafish) embryos and observed that the trained CARE Network reconstructed isometric image data.

## Demo

The trained model is published for demonstration purposes. You can try it via Fiji and KNIME.

To run the demo in Fiji, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/Fiji-Command-%E2%80%93-Isotropic-Reconstruction-(Retina)).

To run the demo in KNIME, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/KNIME-Workflow-%E2%80%93-Isotropic-Reconstruction-(Retina)).

