---
slug: "tubulessrrf"
pretitle: "Deconvolution"
shorttitle: "Microtubules"
longtitle: "Deconvolution (Microtubules)"
inputimage: "images/care/tubules/tubules_srrf_input_hot.png"
outputimage: "images/care/tubules/tubules_srrf_network_hot.png"
tool: care
inoutdata: noisy_gt
videos:
  - url: "ooeHl_qmqzI"
    description: "Reconstruction of diffraction-limited structures at very high frame-rate in rat insulin secretory granules."  
  - url: "r27aIUfQEcQ"
    description: "Reconstruction of diffraction-limited microtubules at very high frame-rate in HeLa cells." 
---

## Authorship

This work (method and data) is part of [Content-aware image restoration: pushing the limits of fluorescence microscopy](http://dx.doi.org/10.1038/s41592-018-0216-7) by Martin Weigert et al. in Nature Methods. 

## Details

Finally we show an example where neither the real biological ground-truth nor the real image degradation process is experimentally accessible, but a *synthetic* generative model of image content and image degradation process is available.

The predictions of a CARE Network trained on fully synthetic training data shows that wide-field acquisitions can yield high-quality reconstructions.

## Demo

The trained model is published for demonstration purposes. You can try it via Fiji and KNIME.

To run the demo in Fiji, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/Fiji-Command-%E2%80%93-Deconvolution-(Microtubules)).

To run the demo in KNIME, [follow these instructions](https://github.com/CSBDeep/CSBDeep_website/wiki/KNIME-Workflow-%E2%80%93-Deconvolution-(Microtubules)).

