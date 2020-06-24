---
layout: toolpage-n2v
title: "FAQ"
permalink: "/tools/n2v/faq"
collection: n2v
backlink:
    title: "N2V overview"
    url: "/tools/n2v/"
---

# Frequently Asked Questions

## How long do I have to train?
Ideally for quite some time. We would suggest to train for at least 100 sepochs with about 300 steps each.
Still, this must be understood as a rule of thumb and the real time you should train depends on your compute hardware (GPU), the amount of data you have, and how hard your denoising problem is.
Good news are that we have so far never seen a Noise2Void network that trained too long, and we expect this to only happen when you train on VERY little data (a few small images).

## What happens if I do not train long enough?
The results might look good at first sight, but are of lesser quality than after longer training.
On two cases you can additionally run into maybe the most annoying problem with short training, namely when you work with 3D images (stacks), or when you work with multi-channel images. Too short training can lead to what we call 'bleed through', i.e. having faint images of the structures of a channels (or focal planes) being faintly visible in other channels (or focal planes). If you want to be sure to avoid this problem, Noise2Void offers an option to train a separate network for each channel. This is very convenient and can be turned on/off via a simple flag for the training method -- very convenient!

## How much data do I need for training?
Don't go much smaller than 5000K pixels, e.g. 2000x3000 or 1000x1000x5 images, etc. The more the merrier! If you use the Fiji plugin, you place many of them in the same folder and run the "train on folder" command pointing to this folder. You can use the same folder for training and validation, it will split up the data automatically and use 90% for training and 10% for validation.

## When is Noise2Void the right tool?
Whenever you have per pixel noise. As soon as you noise is structured (the noise in one pixel depends on neighboring pixel values) you need more advanced methods. One such method by Broaddus et al. is also available within Noise2Void and is called 'Struct N2V'.

## Do training and test data need to be of the same dimensions?
No. You can train on bigger images and run the prediction on smaller images and vice versa. The training data is internally split up into pieces and only a random subset of each batch is fed into the network. You also train on stacks, it'll split them up again into batches internally. 

