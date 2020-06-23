---
slug: "denoisingsem"
pretitle: "Denoising"
shorttitle: "2D SEM data"
longtitle: "Denoising Noise2Noise with multiple noisy copies (2D SEM data)"
inputimage: "images/n2n/sem_input.png"
outputimage: "images/n2n/sem_output.png"  
tool: care
inoutdata: noisy_noisy
---

## Details
This example demonstrates how a denoiser can be trained when only noisy data is available. Please note that this example uses the so-called [Noise2Noise](https://arxiv.org/abs/1803.04189) training, requiring two noisy versions of the exact same field of view to be available.

[Noise2Noise](https://arxiv.org/abs/1803.04189) was first proposed by Lehtinen _et al._ and states that multiple noisy observations of the same structure are sufficient to train content aware image restoration networks. This means that we can replace the ground truth target images with additional noisy acquisitions. This opens the door to many new applications where the acquisition of ground truth data is impossible or very time-consuming.

__Note:__ If you happen to have the possibility to acquire pairs of noisy and clean (ground truth) images, we recommended to use such clean data by training a supervised denoiser. For this, please have a look at the <a href="{{ '/scenarios/denoising2D_HumanU2OS' | prepend: site.baseurl }}">2D denoising scenario</a>.

## Credits
The data was acquired by Réza Shahidi and Gáspár Jékely at University of Exeter and originates from this publication: [Content-aware image restoration for electron microscopy](https://books.google.de/books?hl=en&lr=&id=rn2jDwAAQBAJ&oi=fnd&pg=PA277&dq=info:41WW__W36dwJ:scholar.google.com&ots=xdqzPRk19v&sig=9sxVkiynLPCj9IhHoolchoxTT_U&redir_esc=y#v=onepage&q&f=true) by Tim-Oliver Buchholz _et al._
  
## Demo
In this example a content aware image restoration network was trained on multiple fast scanned Scanning Electron Microscopy (SEM) images. The example notebook can be found [here](https://github.com/juglab/Noise2Noise-with-CSBDeep).
