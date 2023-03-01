
# Crop-Disease-Detection
## Table of Contents

    1    Project Title   
    3    Problem Statement    
    4    Project Description    
    5    Assumptions
    6    Technologies and Tools to be Used    
    7    Advantages of this Project    
    8    Future Scope and further enhancement of the Project  
    9    Conclusion    
    
 ## Project Title
In Agriculture, leaf diseases have grown to be a dilemma as it can cause a significant diminution in both the quality and quantity of agricultural yields. Thus, automated recognition of diseases on leaves plays a crucial role in the agriculture sector. This Crop Disease detection project is based on the same idea which can be used to detect disease in specific crops on which it is trained.

## Problem Statement
In Agriculture sector plants or crops, cultivation has seen fast development in both the quality and quantity of food production. However, the presence of diseases on crops especially on leaves has hindered the quality of agricultural goods. This severe effect can disturb any nation's economy especially of those where 70% of the inhabitants rely on the products from the agricultural sector for their livelihood and endurance. This problem can be solved by the detection of crop diseases and to detect crop disease this project can be used. This project will diagnose the disease based on images of leaves.

## Project Description
This project is created with the goal of detecting the disease of crop through its leaf. In this project concept of deep learning is used which uses the concept of neural networks to solve the critical tasks like human brain. For image classification task since we are classifying leaf image based on its disease so to serve that purpose we have used CNN (Convolution Neural Network) Famous for working with image data since it can detect features automatically in a fast way way because even normal images consists of lakhs of features. In this we have created model with different layers like CNN, Maxpooling, Dropout, Batch Normalization and dropout. For boosting the model accuracy we have used pretrained Alexnet Model weights for our CNN layer so training for those layer have been freezed and rest layers were trained in the training process. Now different steps of projects are explained below-:

### Image Acquisition-: 
The real-time images are fed directly from the camera. For further analysis, proper visibility and easy analysis of images, white background is created because most of the leaves color vary from red to green for exact segmentation.

### Image Pre-processing-: 
Image preprocessing is required to resize captured image from high resolution to low resolution. The image resizing can be done through the process of interpolation. 
Batch Normalization is also used normalize data.

### Feature Extraction and Feature Selection-: 
Feature Extraction is one of the most interesting steps of image processing to reduce the efficient part of an image or dimensionality reduction of interesting parts of an image as a compact feature vector. Feature reduction representation is useful when the image size is large and required to rapidly complete tasks such as image matching and retrieval. This part is handled By our CNN Layer which is used for feature detection and for selection we use Max Pooling and dropout Layer.

### Model Training-:
It is done after model curation which is done on the basis of all above information since we are using deep learning most of tha task or almost all tasks are handled by our model itself so to perform all above operation we define layers in our model. After curation of Model we train our model by setting our Hyper-perameters. After training part is performed our model is ready for the process of Image Classification.

### Image Classification-: 
It consists of model that contains pre-defined patterns that are compared with detected objects to classify them in a proper category. Classification will be executed on the basis of spectral defined feature such as density, texture etc. Image classification is performed using Convolution Neural Networks and Deep Learning, and it has introduced the Convolution Neural Network (CNN) as a new area in machine learning and is applied to detect crop disease through classification of image.
## Assumptions-:
Since model is trained for specific crops only so it can diagnose those specific crops only.
The List of Crops For which this model will be helpful is:


<img src="static/Screenshot_3.png">

The crop which can be used for diagnosis can only diagnose specific disease for which the model is trained. 
The List of crop diseases on Which Model is trained on is:


<img src="static/Screenshot_2.png">


Above image indicates that we have 15 crops on which our model works for 38 specific cases which are basic classes on which our model will perform classification process.


## Technologies and Tools to be Used -:
- Keras -> A High Level Deep Learning API to Use Neural Network in Project.
- Tensorflow -> It is used by keras to perform low level operation or as a Backend Engine. Theano and CNTK can be used in place of Tensorflow
- Jupyter Notebook -> A platform through which you can access all libraries and use them according to your requirement. It is used to implement your Logic.
- Google Colab -> Google Colab can be used as online jupyter notebook since it provides free GPU which are must with this Project because the dataset is Huge.
- Kaggle -> Even kaggle can be used where you can upload your data and work with that data and the dataset of this project is present on kaggle so creating notebook on kaggle will be beneficial.
- Python -> Python is a language through which this whole project is made and it is used to create model via Jupyter notebook libraries
### Advantages of this Project
- Easily detect crop diseases to simplify treatment process.
- One touch process to analyze crop defects.
- The model will also help in improving harvest quality and accuracy, which is known as precision agriculture.
## Conclusions
This project can be used for simplifying the process of crop disease detection. This project follows one touch process for detection of disease in crop if present. By detecting disease one can take steps for treatment of the same. This project will be beneficial on the specific crop category on which it is trained. This project can save a lot of time which is wasted on detection of diseases found in crop that too with good accuracy.

## DataSet Link
- [Dataset](https://datasetsearch.research.google.com/search?query=plant-diseasesdataset&docid=ouHePAWoVIMq2IHEAAAAAA%3D%3D)-> Link of Dataset
