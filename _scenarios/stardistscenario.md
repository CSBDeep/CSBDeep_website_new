---
slug: "stardistscenario"
pretitle: "Segmentation"
shorttitle: "Object Segmentation"
longtitle: "DSB2018"
inputimage: "images/stardist/stardist-input.jpg"
outputimage: "images/stardist/stardist-output.jpg"  
tool: stardist
inoutdata: noisy_gt
---

## Authorship
This example is part of the **[Stardist - Object Detection with Star-convex Shapes](https://github.com/mpicbg-csbd/stardist)** described in the papers: [Cell Detection with Star-convex Polygons. by Schmid *et al* ](https://arxiv.org/abs/1806.03535) and [Star-convex Polyhedra for 3D Object Detection and Segmentation in Microscopy. by Weigert *et al*](http://openaccess.thecvf.com/content_WACV_2020/papers/Weigert_Star-convex_Polyhedra_for_3D_Object_Detection_and_Segmentation_in_Microscopy_WACV_2020_paper.pdf).

## Details
This example is a 2D image of stained nuclei part of the DSB2018 dataset where several nuclei are overlaped, therefore, making it harder to split and segment without taking the risk of creating artifacts in the process.
