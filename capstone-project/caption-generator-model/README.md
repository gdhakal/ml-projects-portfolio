# Automated Image Caption Generator to Assist the Visually Impaired

## Problem Statement

The computer vision research aims to develop an AI technology that can replicate what humans can see and comprehend from their surroundings. There is also another challenge for the computer vision community to develop assistive technology that can help visually impaired people to derive data and information from their surrounding objects and scenes so they can independently navigate in their daily lives. 

The current state of the art image captioning technologies provides a generic description of the image, which might not necessarily answer the intended queries of the visually impaired individuals. Hence, this project entails providing goal-oriented image captioning, in which the captions not only provide a description of a scene from everyday life but it also answers queries of the visually impaired individuals to achieve a particular task. For example, identifying the nutrition content of the food item at the grocery store or providing a feedback caption to turn the flash camera in order to take a recognizable picture of an item due to low light in the room or rotate the object to retrieve nutrition content in the package.

## Introduction

This project aims to develop a machine learning model that generates a goal-oriented image caption in order to make the world more accessible to visually impaired people. 

The scope of this project is to generate a caption of the images taken by the blind on their mobile phone camera. The machine learning model would provide data and information that answers intended queries about the captured image as well as provide feedback to users if they need to augment the object or their environment settings in order to capture a recognizable picture or informative content from the image to answer their given question.

The goal of this project is to assist visually impaired people to derive information that is essential for them to achieve tasks in their daily lives.

## Dataset

Use VIzWiz dataset that contains images taken by blind people: https://vizwiz.org/tasks-and-datasets/image-captioning/. The VizWiz-Captions dataset includes:
- 23,431 training images
- 117,155 training captions
- 7,750 validation images
- 38,750 validation captions
- 8,000 test images
- 40,000 test captions


## References
- https://www.ibm.com/blogs/research/2020/07/image-captioning-assistive-technology/
- https://web.stanford.edu/class/cs224n/reports/custom/report27.pdf
- https://github.com/husthuaan/AoANet