# Image Panorama Stitching

## Description
This repository contains the code and resources for my Image Panorama Stitching project, completed as part of the BBM418 course at Hacettepe University. The aim of this project is to implement a basic form of image stitching, taking two or more input images and merging them together to create a single panoramic image.

## Methodology
1. **Feature Extraction**: Key points are detected in the input images, and local invariant descriptors are extracted using popular algorithms like SIFT, SURF, and ORB.

2. **Feature Matching**: The extracted descriptors from the two input images are compared, and similar features between the images are identified.

3. **Homography Estimation**: With the matched feature vectors, we estimate the homography matrix using the RANSAC algorithm, which represents the geometric relationship between the two images.

4. **Warping Transformation**: The homography matrix is utilized to perform a warping transformation on one image, aligning the matching features in both images to create a seamless panorama.

## Dataset
The dataset used in this project can be accessed from the following link:
[HPatches Dataset](http://icvl.ee.ic.ac.uk/vbalnt/hpatches/)


