---
slug: "segmentationmousenuclei"
pretitle: "Segmentation"
shorttitle: "Mouse nuclei"
longtitle: "Mouse nuclei segmentation and denoising"
inputimage: "images/denoiseg/mousenuclei-input.jpg"
outputimage: "images/denoiseg/mousenuclei-output.jpg"  
tool: denoiseg
inoutdata: noisy_gt
---

## Authorship
This work (method and data) is part of [DenoiSeg: Joint Denoising and Segmentation](https://arxiv.org/pdf/2005.02987.pdf) by Tim-Oliver Buchholz and Mangal Prakash et al. 

## Details

Raw noisy input with denoised and segmentation outputs of a trained DenoiSeg Network on Mouse nuclei dataset. The network was trained using 908 noisy images of size 128x128 and only 38 of those images had segmentation ground truth available.

 We observe that some errors are present in segmentation result which is to be expected since the network was trained on very limited segmentation annotations. But the errors are significantly lesser as compared to results obtained with other baselines trained with limited ground truth annotations. To compare our results with other baselines, [check this page](https://github.com/juglab/DenoiSeg/wiki/Quantitative-segmentation-comparison-for-Mouse-dataset).

## Demo

To reproduce this experiment with our Jupyter notebooks, [follow these instructions](https://github.com/juglab/DenoiSeg).
