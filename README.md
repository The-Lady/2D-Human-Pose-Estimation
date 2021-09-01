2D-Human-Pose-Estimation (CSC 542 Neural Networks Project - Group G33)
======

### Group Project Members
- Aishwarya Seth
- Ishan Bhatt
- Akhil Bommadevara

### Introduction
The system aims to evaluate human poses from a given set of 2D RGB images. It detects poses based on the keypoints detected from the heatmaps of images.

#### Dataset
The dataset used for training is derived from the MPII Human Pose Dataset, with the threshold of number of keypoints visible set to 12 in each image.

#### Methodology
We have used 3 hourglass models stacked one after the other for human pose estimation; the architecture being alternatively known as the stacked hourglass model.

#### Files
- 'Code' directory contains all the files used for processing the data and preparing the dataset. It also contains the model.
- 'Doc' directory contains all the documents related to the project - Proposal, Report, Presentation, Poster and some of the research papers referred.
- 'anno_list.csv' contains the annotations of keypoints in all images.
