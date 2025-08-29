This repo is based on the course/lab [Lab in Signal & Image Processing](https://edu.epfl.ch/coursebook/en/lab-in-signal-and-image-processing-EE-490-F), that I have completed. The main purpose of this repo is to refresh my memory about computer vision, taking it from a low-enough level (lower-level image processing repositories to come).

This repo contains the lab submissions for the course, mainly Jupyter Notebooks, as well as the data used in the lab.

The labs aim to give a quite detailed introduction to image processing, exploring the evolution of image processing tools, from basic algorithms to deep learning methods, with each of the labs focusing on a specific topic:
1. Introduction to Image Processing
2. Object Detection
3. Object Tracking
4. Introduction to Deep Learning


To be able to use the same packages' versions used here:
- We install [anaconda](https://www.anaconda.com/download) with the default settings & options.
- We open the Anaconda prompt.
- We create a conda virtual environment to keep dependencies required separate from your different projects.
- We activate the virtual environment.
- We install the required dependencies.
- Edit & Run the Jupyter Notebooks either on the browser or locally.

```
conda create --name IPLAB python=3.8
conda activate IPLAB
pip install opencv-contrib-python==3.4.17.61 matplotlib jupyter
```