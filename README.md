# DeepVP: Deep Learning for Vanishing Point Detection on 1 Million Street View Images

This repository contains the source code for the DeepVP project, which focuses on vanishing point detection using deep learning techniques on a large dataset of street view images. The project aims to improve the accuracy and robustness of vanishing point detection algorithms compared to traditional methods.

## Abstract
We propose a novel approach to detect vanishing points in images using a convolutional neural network (CNN) trained on a newly collected Google street-view image dataset. By utilizing the camera parameters and road direction data from Google street view, we collected a total of 1,053,425 images with inferred ground-truth vanishing points, along 23 worldwide routes totaling 125,165 kilometers. We then formulate vanishing point detection as a CNN classification problem using an output layer with 225 discrete possible vanishing point locations. Experimental results show that our deep vanishing point system outperforms the state-of-the-art algorithmic vanishing point detector.    We achieved 99% accuracy in recovering the horizon line and 92% in locating the vanishing point within a 5-degree range.


## Key Features
- Utilizes a convolutional neural network (CNN) for vanishing point detection
- Trained on a dataset of 1 million street view images from 23 routes across 21 countries
- Achieves superior accuracy in vanishing point estimation compared to traditional algorithms
- Dataset collection procedure ensures even distribution of vanishing points across images
- Location-insensitive and less center-biased vanishing point detection system

## Pre-fetched Dataset
http://ilab.usc.edu/kai/deepvp/

## Getting Started
1. download the source code: `https://github.com/mezl/deepvp/blob/main/streetview.py`
2. You will need to provide your own Google Map API Key
3. Modify the GPS coordniate for your needs

For more details, refer to the [paper]([link_to_paper](https://github.com/mezl/deepvp/blob/main/Chang_etal18icra.pdf)), [Slides](https://docs.google.com/presentation/d/17WUAewEdUuD2denbpVHo0DzlPr46t5cyEvCngB3MG0M/edit?usp=sharing) and [video](http://www.youtube.com/watch?v=_bD4pqxgCKM).

[![IMAGE ALT TEXT](http://img.youtube.com/vi/_bD4pqxgCKM/0.jpg)](http://www.youtube.com/watch?v=_bD4pqxgCKM "Deep Vp")

### Authors: 
Chang, Chin-Kai; Zhao, jiaping; Itti, Laurent
