# cxrdiagnosis-python
Combination of image enhancement, transfer learning, and machine learning on COVID-19 diagnosis using Chest X-Ray (CXR).

The COVID-19 diagnosis process is started from enhancing CXR images using Contrast Limited Adaptive Histogram Equalization (CLAHE) as image enhancement technique. Then pre-trained InceptionV3 CNN model is utilized in transfer learning process, the main goal of this process is to extract the features based on the enhanced CXR images. The last process is classification where Support Vector Machine machine learning algorithm (SVM) are applied to classify the images (images are separated to 70:30 as training and test set).
