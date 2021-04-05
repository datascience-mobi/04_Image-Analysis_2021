---
output: 
  html_document: 
    keep_md: yes
---
# Topic 4:  Biomedical Image Analysis

Supervisors: 

* PD Dr. Karl Rohr (k.rohr@uni-heidelberg.de)
* Christian Ritter (christian.ritter@bioquant.uni-heidelberg.de)
* Carola Krug      (carola.krug@bioquant.uni-heidelberg.de)
* Leonid Kostrykin (leonid.kostrykin@bioquant.uni-heidelberg.de)

## Introduction

Image analysis methods are important to extract relevant information from biomedical image data.
Typically a large amount of data needs to be analyzed to draw statistically significant conclusions.
Manual analysis of the image data is tedious, time-consuming, and subjective.
Thus, computer-based image analysis is needed, which enables fast, reproducible, and accurate automated analysis of the data.

To extract information from the image data, methods for different image analysis tasks are required. Typical tasks are image preprocessing, feature extraction, segmentation, object recognition, tracking, and image registration. The projects within the topic "Biomedical Image Analysis" comprise different image analysis tasks using different methods and image modalities. The image analysis methods will be implemented in Python using existing libraries (e.g., NumPy, Scikit-learn). 


## Objective

#### Human Face and Digit Recognition

The objective of projects 1 and 2 is to implement and evaluate classification methods for human face and handwritten digit recognition using K-nearest neighbors. For both projects, the first step consists of computing statistical measures for performing data normalization. Second, data dimension reduction should be performed by principal component analysis (PCA) and the results should be visualized. Third, the data set should be split into training and test data sets in order to perform human face or handwritten digit recognition.   

* Project 1: Implementation and evaluation of K-nearest neighbors (KNN) algorithm for human face recognition. 
* Project 2: Implementation and evaluation of K-nearest neighbors (KNN) algorithm for handwritten digit recognition. 

#### Cell Nuclei Segmentation

The objective of projects 3, 4, and 5 is to implement and evaluate methods for segmentation of cell nuclei (Otsu thresholding, region growing, support vector machine). First, an image segmentation method should be implemented. Second, a popular evaluation measure known as "Dice score" should be implemented and tested using synthetically generated images. The methods should be applied to cell nuclei images and the average Dice score should be computed. Third, pre-processing methods such as Gaussian filtering should be investigated to improve the result.

* Project 3: Implementation and evaluation of Otsu thresholding.
* Project 4: Implementation and evaluation of region growing.
* Project 5: Implementation and evaluation of machine learning (support vector machine) segmentation. 


## Description of datasets

#### Human Face and Digit Recognition
The dataset for human face recognition is a subset of the Extended Yale Face Database B of human faces consisting of 2.535 images from 39 subjects. Per subject exist 65 images with different illumination conditions. The images are grayscale images normalized by size (168×192 pixels) and stored as PGM (portable graymap) files. The datset for digit recognition is from the MNIST database (Modified National Institute of Standards and Technology database) of handwritten digits consisting of a training set (60.000 images) and a test set (10.000 images). The images are size-normalized (28×28 pixels) and centered, and stored as csv (comma-separated values) files. Each line of these files represents an image. The first column represents the label (the digit depicted in the image). 

#### Cell Nuclei Segmentation
The image data for cell nuclei segmentation consists of 3 different datasets. The first dataset consists of 6 images showing GFP transfected GOWT1 mouse embryonic stem cells. The images have a size of 1024×1024 pixels and show 10–20 cell nuclei per image. The second dataset consists of 18 images of mouse embryonic cells stained with Hoechst. The images have a size of 1344x1024 pixels and include around 60 cell nuclei per image. The third dataset consists of 4 images with HeLa cells stably expressing H2b-GFP. The images have a size of 1100×700 pixels and show 30–50 cell nuclei per image.



## Literature 

#### Human Face and Digit Recognition
* Gerbrands, J.J. "On the relationships between SVD, KLT and PCA." Pattern Recognition (1981), vol. 14, issues 1-6, pp 375-381
* Belhumeur, P.N., Hespanha, J.P. and Kriegman, D. "Eigenfaces vs. Fisherfaces: Recognition Using Class Specific Linear Projection." IEEE Transactions on Pattern Analysis and Machine Intelligence (1997), vol. 19, pp 711-720.
* Netzer, Y. et al. "Reading Digits in Natural Imageswith Unsupervised Feature Learning." Proceedings of the Workshop on Neural Information Processing Systems (2011)
* Gareth, J. et al. "An introduction to statistical learning." Springer New York (2013), Chapter 4.4

#### Cell Nuclei Segmentation
* Otsu, N. "A threshold selection method from gray-level histograms." IEEE Transactions on Systems, Man, and Cybernetics 9:1 (1979), pp 62-66.
* Ljosa, V., Sokolnicki, K.L. and Carpenter, A.E. "Annotated high-throughput microscopy image sets for validation." Nature Methods 9:7 (2012), pp 637-637.
* Shih, F.Y. and Cheng, S. "Automatic seeded region growing for color image segmentation." Image and Vision Computing (2005), vol. 23, issue 10, pp 877-886
* Szénási, S. "Distributed region growing algorithm for medical image segmentation." International Journal of Circuits, Systems and Signal Processing (2014), vol. 8, pp 173-181
* Lin, Z., Jin ,J.S. and Talbot, H. "Unseeded region growing for 3D image segmentation." Proceedings of the Pan-Sydney Area Workshop on Visual Information Processing (2000), vol. 2, pp 31-37
* Burges, C.J.C. "A Tutorial on Support Vector Machines for Pattern Recognition." Data Mining and Knowledge Discovery (1998), vol. 2, pp. 121-167


## How to structure your project

### Project proposal

For all projects within the topic "Biomedical Image Analysis" the first task 
is to define a **project proposal**, which should include

* List of planned analysis steps
* Milestones (important achievements)
* Deliverables (result for each milestone)
* Approximate timetable

The project proposal will be presented three weeks after the beginning of the semester (10 min presentation + 5 min discussion). 








