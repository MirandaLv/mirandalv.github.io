---
title: "A multi-glimpse deep learning architecture to estimate socioeconomic census metrics in the context of extreme scope variance"
collection: publications
excerpt: 'This study investigates the application of Convolutional Neural Networks (CNNs) for estimating census variables across diverse Mexican municipalities, ranging from small to large geographic extents. Utilizing deep learning techniques, particularly a multi-glimpse recurrent attention model, the research demonstrates promising results with nearly half of the tested variables (22 out of 52) achieving r2 values greater than 0.75, indicating the potential of satellite imagery for estimating socioeconomic factors in both historical periods and contemporary inaccessible regions.'
date: 2024-01-01
venue: 'International Journal of Geographical Information Science'
paperurl: 
citation: 
---
Convolutional Neural Networks (CNNs) are leveraged for a wide range of satellite imagery information extraction tasks. However, for tasks which seek to estimate aggregated information across highly variable geographic extents, existing techniques are subject to critical limitations. We engage with a specific case study exploring this challenge: estimating census variables across 2,358 Mexican municipalities, which range in scope from 2.21 km2 ( ̃74,000 30 meter pixels) to 72,417.9 km2 ( ̃2.4 billion pixels). Building on recent literature which has illustrated the capability of deep learning to extract socioeconomic information from satellite imagery, we specifically seek to establish baseline metrics of error that might be expected when estimating a range of census variables based on coarse-resolution (Landsat) satellite imagery alone. For each of 52 variables, we implement a multi-glimpse recurrent attention model, in which we parametrically determine subsets of each municipality to sample across iterative steps. Results of a 5-fold validation indicate that nearly half of the tested variables (22) can be estimated with r2 values greater than 0.75. Results suggest considerable promise for the use of satellite imagery to estimate socioeconomic factors in both historic time periods for which surveys were not conducted, as well as contemporary inaccessible regions.

[Download paper here](http://mirandalv.github.io/files/DLAttentionGlimpse.pdf)

Citation: Runfola, D., Stefanidis, A., Lv, Z., O'Brien, J., and Baier, H., Accepted. A multi-glimpse deep learning architecture to estimate socioeconomic census metrics in the context of extreme scope variance. International Journal of Geographical Information Science.