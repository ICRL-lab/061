# Recyclables Detection in Garbage

## Introduction

Recyclables detection in garbage using YOLOv8 leverages advanced object detection algorithms to accurately identify and classify recyclable materials like plastics, metals, and paper in waste streams. This AI-driven approach enhances waste sorting efficiency and promotes sustainable recycling practices.

## Dataset

We have used a custom dataset consisting of 5000 images collected from different sources.

### Dataset Statistics:

here are the sample statistics of the data

- **Name:** Garbage Dataset
- **Mode:** Image Data
- **Number of Samples:** 
  - Train: 5000 
  - Test: 1000
- **Type:** Detection
- **Modality:** Colour-images
- **Number of Classes:** 6
- **Classes Name:** 
  - Plastic
  - Cupboard
  - Metal
  - Glass
  - Paper
  - Trash

## Pre-processing

The preprocessing steps of the proposed project are the following:

1. Image resizing to a standard dimension.
2. Normalization of pixel values.
3. Data augmentation (rotation, flipping, etc.) to increase the dataset size and variability.
4. Splitting the dataset into training and validation sets.

## Models

For the Recyclables Detection in Garbage following models were trained with the default parameters:

- **YoloV8**

## Results

The results of the trained model are the following:

- MAP: 0.83
- IOU: 0.75


## Dependencies

- Ultralytics
- torch
- torchvision
- OpenCV
- Numpy

<br>

# Author
**Muhammad Kamran** <br>
**Research Officer** <br>
***National Center of Artificial Intelligence (NCAI)*** <br>
*AL-Khawarizmi Institute of Computer Science (KICS)* UET Lahore <br>
