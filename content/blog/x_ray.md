---
author: Georgi Demirev
date: "2018-10-17T11:33:12+06:00"
description: Automatic Detection of Thoracic Diseases based on X-Ray Images
image: images/blog/x_ray.jpg
title: Automatic Detection of Thoracic Diseases based on X-Ray Images
summary: The client wanted to develop an automated system for recognizing and localising thoracic diseases ...
---

# The Problem:

The client wanted to develop an automated system for recognizing and localising thoracic diseases based on xray images.

# Our Approach:

A computer vision model was developed and trained to predict 8 different conditions on several hundred thousands of xray images. Each label prediction was accompanied by a heatmap, showing the most likely location of the disease. Due to the small amount of training data, a custom network topography optimization algorithm was developed, based on a separate constructor RNN, learning to build the predictive CNN iteratively using reinforcement learning.

# Deliverables:

A prototype model using convolutional neural networks and recurrent neural networks was developed and presented.
