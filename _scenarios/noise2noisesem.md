---
slug: "denoisingsem"
pretitle: "Denoising"
shorttitle: "SEM"
longtitle: "SEM 2D Denoising"
inputimage: "images/n2n/sem_input.png"
outputimage: "images/n2n/sem_output.png"  
tool: care
inoutdata: noisy_noisy
---

## Authorship
The data was acquired by Réza Shahidi and Gáspár Jékely at University of Exeter and originates from this publication: [Content-aware image restoration for electron microscopy](https://books.google.de/books?hl=en&lr=&id=rn2jDwAAQBAJ&oi=fnd&pg=PA277&dq=info:41WW__W36dwJ:scholar.google.com&ots=xdqzPRk19v&sig=9sxVkiynLPCj9IhHoolchoxTT_U&redir_esc=y#v=onepage&q&f=true) by Tim-Oliver Buchholz _et al._

## Details
[Noise2Noise](https://arxiv.org/abs/1803.04189) was first proposed by Lehtinen _et al._ and states that multiple noisy observations of the same structure are sufficient to train content aware image restoration networks. This means that we can replace the ground truth target images with additional noisy acquisitions. This opens the door to many new applications where the acquisition of ground truth data is impossible or very time-consuming.

__Note:__ If you can get your hands on clean ground truth images, we recommended using them.

  
## Demo
In this example a content aware image restoration network was trained on multiple fast scanned Scanning Electron Microscopy (SEM) images. The example notebook can be found [here](https://github.com/juglab/Noise2Noise-with-CSBDeep).
