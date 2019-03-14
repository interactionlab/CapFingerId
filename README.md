# Finger Identification on Capacitive Touchscreens using Deep Learning
This repository contains the data set and scripts for the IUI '19 paper on "Investigating the Feasibility of Finger Identification on Capacitive Touchscreens using Deep Learning".

## Abstract
Touchscreens enable intuitive mobile interaction. However, touch input is limited to 2D touch locations which makes it challenging to provide shortcuts and secondary actions similar to hardware keyboards and mice. Previous work presented a wide range of approaches to provide secondary actions by identifying which finger touched the display. While these approaches are based on external sensors which are inconvenient, we use capacitive images from mobile touchscreens to investigate the feasibility of finger identification. We collected a dataset of low-resolution fingerprints and trained convolutional neural networks that classify touches from eight combinations of fingers. We focused on combinations that involve the thumb and index finger as these are mainly used for interaction. As a result, we achieved an accuracy of over 92% for a position-invariant differentiation between left and right thumbs. We evaluated the model and two use cases that users find useful and intuitive. We publicly share our data set (CapFingerId) comprising 455,709 capacitive images of touches from each finger on a representative mutual capacitive touchscreen and our models to enable future work using and improving them.

<img src="https://github.com/interactionlab/CapFingerId/blob/master/images/hand.jpg" height="300px"> <img src="https://github.com/interactionlab/CapFingerId/blob/master/images/cap_img.png" height="300px">

This work can be cited as follows:
<pre>
@inproceedings{le2019investigating,
author = {Le, Huy Viet and Mayer, Sven and Henze, Niels},
title = {Investigating the Feasibility of Finger Identification on Capacitive Touchscreens using Deep Learning},
booktitle = {Proceedings of the 24th International Conference on Intelligent User Interfaces},
series = {IUI '19},
year = {2019},
isbn = {978-1-4503-6272-6},
location = {Marina del Ray, CA, USA},
numpages = {15},
publisher = {ACM},
address = {New York, NY, USA},
keywords = {touchscreen, machine learning, finger-aware interaction},
url = {http://doi.acm.org/10.1145/3301275.3302295},
doi = {10.1145/3301275.3302295},
acmid= {3302295}
}
</pre>
