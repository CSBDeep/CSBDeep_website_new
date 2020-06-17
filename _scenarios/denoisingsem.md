---
slug: "denoisingsem"
pretitle: "Denoising"
shorttitle: "SEM"
longtitle: "SEM 2D Denoising"
inputimage: "images/n2v/input.jpg"
outputimage: "images/n2v/output.jpg"  
tool: n2v
videos:
  - url: DJw2VMlDsME
    description: "Training a U-Net with Noise2Void on a single noisy Scanning Electron Microscopy (SEM) image and denoising it."
---

## Authorship

The data was acquired by Réza Shahidi and Gáspár Jékely at University of Exeter and originates from this publication: [Content-aware image restoration for electron microscopy](https://books.google.de/books?hl=en&lr=&id=rn2jDwAAQBAJ&oi=fnd&pg=PA277&dq=info:41WW__W36dwJ:scholar.google.com&ots=xdqzPRk19v&sig=9sxVkiynLPCj9IhHoolchoxTT_U&redir_esc=y#v=onepage&q&f=true) by Tim-Oliver Buchholz _et al_.

## Details
The model was trained and the output predicted by using the `train + predict` command of Noise2Void in Fiji. 
  
## Demo
For demonstration purposes, the trained model was uploaded to the [BioImage Model Zoo](https://bioimage.io), you can download it [here](https://bioimage.io/?model=N2V%20SEM%20Demo). 

The downloaded model can be used for prediction via the `predict` command of Noise2Void in Fiji. 
