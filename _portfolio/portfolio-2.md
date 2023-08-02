---
title: "Creating Segmentation Maps using Style GAN"
excerpt: "Short description of portfolio item number 1<br/><img src='https://www.cityscapes-dataset.com/wordpress/wp-content/uploads/2015/07/zuerich00.png'>"
collection: portfolio
type: "BSc Final Project B"
date: 2021-06-01
location: "Signal and Image Processing Lab, Electrical Engineering department, Technion"
---

### [Project Github Repository](https://github.com/shani1610/SegmentationMapStyleGan) | [Project Report (Hebrew)](https://drive.google.com/file/d/1Oc4AkuyXtDDr91SDA__4GwEamimEKxdS/view?usp=sharing) | [Youtube Demo of styleGAN training process](https://www.youtube.com/watch?v=g7-KP39NPG4)

Students: [Inbal Aharoni](mailto:AHARONINBAL@gmail.com),  [Shani Israelov](mailto:shani1610@gmail.com), Supervised by: [Idan kligvasser](mailto:kligvasser@gmail.com)

The use of GAN has drastically affected low-level vision in graphics, particularly in tasks related to image creation and image-to-image translation. Today the training process, despite all the latest developments, is still unstable. 

Given a semantic segmentation map in which we can separate and look at each pixel in the mage and tag it to the relevant class it represents, we can with the help of GAN produce images based on this map and hope to reach a more stable model. With the success of GANs we produced segmentation maps. With these maps and with the help of the generative model we can get a semantic understanding of the data set and even create completely new scenes.

We simplified the training process of unconditional GAN&#39;s. The training process carried out in two stages. We first created a segmentation map and then created a realistic image from it by the help of SPADE. In the next stage we compared ,by FID and visually, our training process results to results from a process that use only
unconditional GAN. Our training process achieved better results.