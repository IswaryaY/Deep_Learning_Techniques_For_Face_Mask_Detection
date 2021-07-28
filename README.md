# Deep_Learning_Techniques_For_Face_Mask_Detection

[![N|Solid](https://www.mdpi.com/sensors/sensors-20-05236/article_deploy/html/images/sensors-20-05236-g008b.png)](https://nodesource.com/products/nsolid)

> In the recent trend of the Novel coronavirus, it's mandatory to wear a mask every time. You cannot roam outside and in a public place without a face mask to protect yourself from the virus. There are security checks that have been set up at each public shop or public place to verify if people are following the rules for the face mask. There is a dedicated person who is always present as a security guard just to check if we are wearing a face-covering mask or not. So, from the current situation, we decided to build a model which will be helpful for society in this pandemic. A model which can detect if a person is wearing a face mask or not based on trained images with three colors channels (RGB). This analysis is based on deep learning and transfers learning algorithm which can process images.
Deep learning is the process of computers learning to think by mimicking the architecture of the human brain. Masks are one of the few COVID-19 precautions accessible in the absence of vaccination, and they serve a critical role in preserving people's health from respiratory illnesses. It is feasible to build a model to recognize persons wearing masks, not wearing masks, or wearing masks incorrectly using this dataset. 7553 RGB pictures are divided into two folders: with mask and without a mask. Label with mask and without a mask are the two types of images. The number of photographs of faces with masks is 3725, while the number of photos of faces without masks is 3828.

## DATA DESCRIPTION
In recent trend in world wide Lockdowns due to COVID19 outbreak, as Face Mask is became mandatory for everyone while roaming outside, approach of Deep Learning for Detecting Faces With and Without mask were a good trendy practice. Here I have created a model that detects face mask trained on 7553 images with 3 color channels (RGB).
On Custom CNN architecture Model training accuracy reached 94% and Validation accuracy 96%.

#### Content
Data set consists of 7553 RGB images in 2 folders as withmask and withoutmask. Images are named as label withmask and withoutmask. Images of faces with mask are 3725 and images of faces without mask are 3828.

#### Acknowledgements
I have taken 1776 images including both With and Without Face Mask images from Prajna Bhandary's Github account
https://github.com/prajnasb/observations

Remaining 5777 images are collected and filtered from Google search engine.

3725 Images of Face with Mask

3828 Images of Face without Mask.



## OUTCOMES

> Modern facial recognition software analyzes the features surrounding the eyes, nose, mouth, and ears to identify a person whose photograph has already been provided, either by the person or by a criminal database. Wearing a mask prevents this recognition, which is a problem that many systems have already met and handled. Apple's FaceID, which uses facial recognition to unlock iPhones, recently launched a system upgrade that can detect when a person is wearing a mask, for example. Instead than forcing the user to pull down their face covering, the update immediately recognizes a covered mouth and nose and prompts them to enter their passcode.


## Explanatory analysis 
##### GLIMPS OF EXPLANATORY ANALYSIS

###### Training portion of face mash detection dataset
[![N|Solid](https://github.com/IswaryaYogeashwaran/Deep_Learning_Techniques_For_Face_Mask_Detection/blob/main/Train_dataset.png?raw=true)](https://nodesource.com/products/nsolid)
###### validation portion of face mash detection dataset
[![N|Solid](https://github.com/IswaryaYogeashwaran/Deep_Learning_Techniques_For_Face_Mask_Detection/blob/main/validation_dataset.png?raw=true)](https://nodesource.com/products/nsolid)

###### Accuracy of the model
[![N|Solid](https://github.com/IswaryaYogeashwaran/Deep_Learning_Techniques_For_Face_Mask_Detection/blob/main/Accuracy.png?raw=true)](https://nodesource.com/products/nsolid)

## TOOLS USED
- TensorFlow
- Keras
- Google colab
- python
