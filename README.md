# U-Net Segmentation

This repository contains the project done as a part of CS736: Medical Image Computing at IIT Bombay in Spring 2022.

---

# Problem Statement

The project aims to solve a medical image segmentation challenge by ISBI known as the ISBI Cell Tracking Challenge where we are provided with EM slices of ventral nerve cord and we need to segment out the cells present in those EM slices. A typical example of this image segmentation task is shown below :-

Input Image             |  Segmented Output Image
:-------------------------:|:-------------------------:
![input](https://github.com/Adu3108/UNet-Segmentation/assets/81511060/ca538bc7-b1eb-4bde-b6cc-9e6d25555256) | ![output](https://github.com/Adu3108/UNet-Segmentation/assets/81511060/258befac-77f7-4d85-b935-5cd0d36de90d)

In the segmented output image, the white regions correspond to the pixels of segmented objects (cells) and the black boundaries correspond to the cell membranes.

---

# Our Approach

We have implemented the U-Net, a form of Convolutional Neural Networks for performing the image segmentation task. The architecture of this network is given below :- 

<p align="center">
  <img width="736" alt="Unet" src="https://github.com/Adu3108/UNet-Segmentation/assets/81511060/312ac115-71d1-4796-97b3-eaa87d55009e">
</p>

We compared the results obtained from the U-Net Network with those obtained from traditional segmentation methods such as K-Means Clustering algorithm.

---

# References

[U-Net Network](https://arxiv.org/pdf/1505.04597.pdf)

[ISBI Cell Tracking Challenge](https://imagej.net/events/isbi-2012-segmentation-challenge)
