# Melanoma Detection Assignment
> 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1:

The model was extremely overfitting in our case and the validation accuracy was very low. we had to use an augmentation method to ensure that the model works better

- Conclusion 2:

we used basic augmentation and the validatiion accuracry still did not make a huge difference in the model's result. we did random flip, randomcrop to achieve this.
considering that the model was overfitting, we considered to further finetune the data.

- Conclusion 3: 

Data Imbalance was identified in the data and this was remediated using augmentor model. 

- Conclusion 4: 

Post augmenting the data and fixing data imbalance, the results were impressive .. we got an impressive 95% accuracy in training and 83%+ validation accuracy. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Keras
- Tensorflow
- matplotlib
- seaborn
- glob

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by Upgrad team and thanks to all the upgrad professors for motivating and training us on the CNN models and such.



## Contact
Created by [@Surendra-Dhondale] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->