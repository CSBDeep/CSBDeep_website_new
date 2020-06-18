---
slug: "segmentationflywing"
pretitle: "Segmentation"
shorttitle: "Flywing"
longtitle: "Flywing segmentation and denoising"
inputimage: "images/denoiseg/flywing-input.jpg"
outputimage: "images/denoiseg/flywing-output.jpg"
tool: denoiseg
inoutdata: noisy_gt
---

## Authorship
This work (method and data) is part of [DenoiSeg: Joint Denoising and Segmentation](https://arxiv.org/pdf/2005.02987.pdf) by Tim-Oliver Buchholz and Mangal Prakash et al. 

## Details

Raw noisy input with denoised and segmentation outputs of a trained DenoiSeg Network on Flywing dataset. The network was trained using 1428 noisy images of size 128x128 and only 5 of those images had segmentation ground truth available.

We observe that some errors are present in segmentation result which is to be expected since the network was trained on very limited segmentation annotations. But the erros are significantly lesser as compared to results obtained with other baselines trained with limited ground truth annotations. To compare our results with other baselines, [check this page](https://github.com/juglab/DenoiSeg/wiki/Quantitative-segmentation-comparison-for-Flywing-dataset).

## Demo

To reproduce this experiment with our Jupyter notebooks, [follow these instructions](https://github.com/juglab/DenoiSeg).

