# cxrdiagnosis-python
Combination image enhancement, transfer learning, and SVM on CXR diagnosis.

The diagnosis process is started from enhancing CXR images using Contrast Limited Adaptive Histogram Equalization (CLAHE) as image enhancement technique. Then pre-trained InceptionV3 CNN model is utilized in transfer learning process, the main goal of this process is to extract the features based on the enhanced CXR images. The last process is classification where Support Vector Machine algorithm (SVM) with 4 kernels are applied to classify the images (images are separated to 70:30). 
