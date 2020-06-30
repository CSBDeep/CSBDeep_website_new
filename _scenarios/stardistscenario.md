---
slug: "stardistscenario"
pretitle: "Segmentation"
shorttitle: "Object Segmentation"
longtitle: "Nucleus Segmentation with StarDist in 2D (DSB2018 data)"
inputimage: "images/stardist/stardist-input.jpg"
outputimage: "images/stardist/stardist-output.jpg"  
tool: stardist
inoutdata: noisy_gt
videos:
  - url: Amn_eHRGX5M
    description: "StarDist webinar held during the NEUBIAS Academy 2020."
---

## Authorship
This example is part of the **[Stardist - Object Detection with Star-convex Shapes](https://github.com/mpicbg-csbd/stardist)** described in the papers: [Cell Detection with Star-convex Polygons. by Schmidt *et al* ](https://arxiv.org/abs/1806.03535) and [Star-convex Polyhedra for 3D Object Detection and Segmentation in Microscopy. by Weigert *et al*](http://openaccess.thecvf.com/content_WACV_2020/papers/Weigert_Star-convex_Polyhedra_for_3D_Object_Detection_and_Segmentation_in_Microscopy_WACV_2020_paper.pdf).

## Details
This example is a 2D image of stained nuclei part of the DSB2018 dataset where several nuclei are overlapped, therefore, making it harder to split and segment without taking the risk of creating artifacts in the process.

For the full documentation and more detailed examples please have a look at the official [StarDist project page](https://github.com/mpicbg-csbd/stardist).
