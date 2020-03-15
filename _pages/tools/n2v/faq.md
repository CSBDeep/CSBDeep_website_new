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
Longer. 100 sepochs with 300 steps each for example.

## How much data do I need for training?
Don't go much smaller than 5000K pixels, e.g. 2000x3000 or 1000x1000x5, ... The more the merrier! If you use the Fiji plugin, you place many of them in the same folder and run the "train on folder" command pointing to this folder. You can use the same folder for training and validation, it will split up the data automatically and use 90% for training and 10% for validation.

## What about SEM / TEM / CMOS?

## Do training and test data need to be of the same dimensions?
No. You can train on bigger images and run the prediction on smaller images. The training data is internally split up into pieces and only a random subset of each batch is fed into the network. You also train on stacks, it'll split them up again into batches internally. 