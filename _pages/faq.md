---
title: "Frequently Asked Questions"
permalink: /faq
name: faq
layout: page
---

## I have a question, but the answer is not on this page. What do I do now?
The answer is simple and universally true: ask your question on the [image.sc forum](https://forum.image.sc).
This is, by the way, also the right answer for any other question you might have in the context of bioimage analysis. The forum is very active and many intelligent and very helpful and friendly people will try to help you best they can. Enjoy!

## What is training?
Artificial neural networks are designed to solve specific tasks, like denoising an image or segmenting cells. Networks need to be trained. The training process includes feeding data into the network. The network will then learn characteristics of the input and it's weights will iteratively be adjusted to solve the problem specific to the provided input data. While training takes hours to complete, predictions are typically much, much faster.

## What is prediction?
A trained network can be used to predict the correct answer for a given input. This input it typically not the same as the one used during training. Still, it is important the the inputs used during training and later during the prediction phase are of the same nature. If you train on images of cute little cats, the network will most likely not produce any useful outputs on images of membrane labeled epithelia cells. Hence, any user of neural network based methods have to be careful to not violate this important rule. 

## I don't want to train (at least not for many hours).
Me neither! But chances are, that you can't avoid this if you want to get optimal results. Typically you see after some minutes of training already if the training goes in a promising direction. But don't be fooled! Networks learn like many of us -- its fast to learn initially, but takes much, much longer to do a convincing job all the time. 

## Can I just use a trained network from my colleage/collaborator?
The immediate answer we give today is: NO! Don't risk it! Once you learn how to train a network, it quickly becomes a routine job.
The footnote to the initial answer is slightly more complicated. For example, there are some networks trained on a wide range of diverse data and their creators claim that you can use them on many types of inputs. While potentially true, this is not typically done on networks trained within our CSBDeep framework (StarDist being a notable exception). Still, even such networks do NOT work on all immaginable images and you better know exactly what you're doing (or at least check all results before using the predictions for further analysis). 
Another case where it is ok to reuse a network is if you know with certainty that it was trained on the same kind of sample, using the same microscopy setting (same microscope, same lense, same everything). Someone in a facility might, for example, train a network that can then be reused for all data being acquired with one very specific protocol. 

## How can networks be exchanged?
If someone trains a network for you and now you simply want to only use this network on more (suitable) data -- how would you do that?
Its actually quite easy. Virtually all CSBDeep based methods can export trained networks into a ZIP file. This file can then either be loaded again in Python, or in some cases even in a suitable Fiji plugin we created. You can find more detailed information on the pages of the respective tools.

## Training is unbelievable slow... could it be that something is wrong? 
As we said above, predictions are quite fast and even doing them on the CPU of your computer might be fast enough to be feasible. This is not true for training and you absolutely want to perform training on a GPU (Graphics Processing Unit).
It might be that your computer does not have a compatible (NVidia) GPU, or that you miss suitable drivers for the training procedure to use your GPU.
If you experience your problems in Fiji, we have collected some resources for how to support GPU usage [here](https://github.com/CSBDeep/CSBDeep_website/wiki/CSBDeep-in-Fiji-–-Installation).
If this happens also within Python (Jupyter), it might be best to ask on the [image.sc forum](https://forum.image.sc).

## I made something new based on CSBDeep. Can I add this new tool onto this website?
Awesome! Kodus for doing that! Please contact anyone of us, e.g. Florian Jug or Martin Weigert, and we will be happy to chat with you about that!
