# Optical Character Recognition and Feature Extraction
This repository contains implementation of optical character recognition and feature extraction using both MLP and CNN.

## Files included
**src/util.py** contains derivative of various activation functions  
**src/nn.py** contains functions for constructing a fully-connected neural network  
**src/fakeDataTest.py** training/testing with a single-layer fully-connected neural network on randomly generated dataset  
**src/realDataTest.py** training/testing with a single-layer fully-connected neural network on NIST36 dataset  
**src/findLetters.py**  function for extracting texts from neighboring pixels and plotting with bounding boxes  
**src/textExtraction.py** extracting hand-written texts from image and classified using nn trained in realDataTest.py  
**src/vaeCompression.py** compressing NIST36 dataset images with a 2-hidden-layer vanilla Autoencoder  
**src/pcaCompression.py** compressing NIST36 dataset images using principal component analysis approach  
**src/pytorchMLP.py** implementing a fc nn using Pytorch  
**src/pytorchCNN.py** implementing a CNN using Pytorch  
**src/cnnVisualization.py** visualizing feature maps and filters in a trained cnn  

## Hand-written texts extraction and recognition
<img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/images/02_letters.jpg" width=30%><img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_1.png" width=40%><img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_2.png" width=20%>

## Image compression  
<img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_3.png" width=40%><img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_4.png" width=40%>

## Convolutional network visualization
### Dataset
<img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_5.png" width=50% height=50%>

### Accuracy
<img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_6.png" width=40%><img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_7.png" width=40%>
### Visualization
<img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_8.png" width=40%><img src="https://github.com/ziliHarvey/Optical-Character-Recognition/raw/master/results/Figure_9.png" width=40%>
