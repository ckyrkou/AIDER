# AIDER:  Aerial Image Database for Emergency Response Applications

## Overview
#Notice
Preliminary Dataset: This Dataset is preliminary, an extented version will be uploaded soon.

The dataset construction involved manually collecting all images for four disaster events Fire/Smoke, Flood, Collapsed Building/Rubble, and for Traffic Accidents, as well as for normal case that does not signal the presence of a disaster.

The aerial images of these disaster classes were collected from multiple sources such as the world-wide-web (e.g. google images, bing images, youtube, news agencies web sites, etc.), other databases of general aerial images, and images collected using our own UAV platform. During the data collection process the various disaster events were captured with different resolutions and under various condition with regards to illumination and viewpoint.

It is advised to further enhance the dataset that random augmentations are probabilistically applied to each image prior to adding it to the batch for training. Specifically there are a number of possible transformations such as geometric (rotations, translations, horizontal axis mirroring, cropping and zooming), as well as image manipulations (illumination changes, color shifting, blurring, sharpening, and shadowing).

Snapshot of some of the images below:

<img src="./images/AIDER.png" width="512">
