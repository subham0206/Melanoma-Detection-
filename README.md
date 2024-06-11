# Melanoma-Detection
> build a multiclass classification model using a custom convolutional neural network in TensorFlow.

> Find detailed project along with dataset on collab: **https://drive.google.com/drive/folders/1TUwIoAWjjBoprDRiOOWRRCna_-j6gaPq?usp=sharing**

> Find detailed project along with dataset on kaggle: **https://www.kaggle.com/code/subhamsrivastavaml/skin-cancer-detection**

 

# Problem statement
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Steps Followed in the Projects] (#Steps Followed in the Projects)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- To build a CNN based model which can accurately detect melanoma.
- Melanoma is a type of cancer that can be deadly if not detected early.
- It accounts for 75% of skin cancer deaths. 
- A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).
- All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


## Steps Followed in the Projects

- Data Reading/Data Understanding
- Dataset Creation
- Dataset visualisation 
- Model Building & training
- Build a CNN model with appropriate optimiser and loss function for model training
- Train the model
- Write your findings after the model fit. You must check if there is any evidence of model overfit or underfit.
- Chose an appropriate data augmentation strategy to resolve underfitting/overfitting 
- Model Building & training on the augmented data
- Class distribution: Examine the current class distribution in the training dataset 
- Handling class imbalances
- Build a final CNN model, which can accurately detect 9 classes present in the dataset.
- Write your findings after the model fit.



## Conclusions
- Accuracy has been improved significantly after treating the class imbalance using augmentation.
- Train Accuracy 88% and Validation Accuracy 74%, with very less loss in train and validation.
- Though i have implemented dropout but still i can see some evidence of overfitting.(increasing some more layers of dropout would certainly reduce overfitting & increasing epoch cycle     will help improve accuracy further, but couldn't execute it due to hardware restriction)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- pathlib
- keras
- tensorflow
- matplotlib


## Acknowledgements
Give credit here.
- This project was inspired by International Skin Imaging Collaboration (ISIC) 
- I would like to thank my upGrad Buddy and tutor for assisting me to complete this assignment
- Reference: Stack Overflow, Wikipedia & Google Collab 


## Contact
Created by [@subham0206] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [https://github.com/subham0206/Melanoma-Detection-.git](). -->
