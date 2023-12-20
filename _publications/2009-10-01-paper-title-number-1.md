---
title: "pyShore: A deep learning toolkit for shoreline structure mapping with high-resolution orthographic imagery and convolutional neural networks"
collection: publications
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'This research investigates the utility of deep learning for mapping shoreline armoring structures, emphasizing computationally efficient methods for semi-automated delineation using high-resolution imagery. The ResNet18-based Pyramid Attention Network (PAN) architecture demonstrated a 72% overall accuracy, with notable precision of 80% and 94% for breakwaters and groins, respectively. This lightweight implementation enables swift processing of 1.5 kilometers of shoreline in 1.4 seconds (GPU) to 2.16 seconds (CPU) within simulated user environments. The study also introduces pyShore, providing a deep learning algorithm for human coders to incorporate into a semi-automated workflow.'
date: 2023-01-01
venue: 'Computers & Geosciences'
paperurl: 
citation: 
---
The process of mapping shoreline structures (i.e., riprap, groins, breakwaters or bulkheads) is heavily reliant on in-situ field surveys and manual delineation using orthoimagery or aerial imagery. These processes are time and resource intensive, resulting in update times of longer than a decade for larger waterbodies. In this study, we explore the effectiveness of a deep learning approach to map shoreline armoring structures from remotely sensed high-resolution imagery. We focus on computationally efficient techniques which can be deployed in desktop environments similar to those used by human coders today, with the goal of providing a semi-automated technique which reduces the total amount of time required to delineate shoreline structures. We test a range of architectures using a dataset of over 10,000 observations of four classes of shoreline structure, finding that a ResNet18 based Pyramid Attention Network (PAN) architecture achieves 72% overall accuracy (60 cm resolution), with 80% and 94% prediction accuracy in breakwater and groins, respectively. This relatively lightweight implementation enabled a 1.5 kilometers of shoreline to be processed in 1.4 s (GPU) to 2.16 s (CPU) in simulated user environments. Finally, we present pyShore, an implementation of this deep learning algorithm made available for human coders to apply as a part of a semi-automated workflow.

[Download paper here](https://www.sciencedirect.com/science/article/pii/S009830042200245X)
