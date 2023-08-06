
# plant seedling classification

Plant seedling classification is a computer vision and machine learning task that involves identifying and categorizing different species of plant seedlings based on images of their seedlings. The goal is to develop a model that can accurately distinguish between various plant species at an early stage, which can be useful in agriculture, horticulture, and biodiversity conservation.
the model can be downloaded from [here ](https://drive.google.com/file/d/1Jlt97VQ48WXctaAGStBt50tp_LHN24G6/view?usp=drive_link)




## Table of content

* Demo
* Data Source
* Overview
* Installation
* References
## Demo






![App Screenshot](https://github.com/Ashoktripathi13/plant_seedling_classification/blob/master/screenshot/1690832870846.png?raw=true)

![App Screenshot](https://github.com/Ashoktripathi13/plant_seedling_classification/blob/master/screenshot/1690832870858.png?raw=true)
![App Screenshot](https://github.com/Ashoktripathi13/plant_seedling_classification/blob/master/screenshot/1690832870871.png?raw=true)
![App Screenshot](https://github.com/Ashoktripathi13/plant_seedling_classification/blob/master/screenshot/pic.PNG?raw=true)


## Data source

The dataset is available here https://www.kaggle.com/c/plant-seedlings-classification/data?select=train The Dataset contains images of plant seedlings at various stages of grown. Each image has a filename that is its unique id. The dataset comprises 12 plant species. The goal of the project is to create a classifier capable of determining a plant's species from a image.

The list of Species is as follows: 
* Black-grass ,Charlock Cleavers, Common Chickweed ,Common wheat ,Fat Hen, Loose Silky-bent ,Maize, Scentless Mayweed, Shepherds Purse, Small-flowered Cranesbill ,Sugar beet
## Overview

This is an plant seedling classification and  web application . We used transfer learning to classify images. Pre-train model like InceptionResNetV2 is used for transfer learning. The goal is to develop a model that can give more accuracy on the different species of plant.

## Installation

The code is written in Python . The required packages and libraries for this project are:

* openCV
* tensorflow
* Keras
* scikit-learn
* numpy
* pandas
* streamlit 
* Pillow

## References

* http://dstore.alazhar.edu.ps/xmlui/bitstream/handle/123456789/279/ASHPSCv2.pdf?sequence=1&isAllowed=y

* https://iopscience.iop.org/article/10.1088/1742-6596/2161/1/012006/pdf
