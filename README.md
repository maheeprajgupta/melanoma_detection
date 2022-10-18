# Melanoma Detection Case Study
>  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 


## Table of Contents
* [General Info](#general-information)
* [Findings](#findings)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)




## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- What is the business probem that your project is trying to solve?
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75 percent of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the dataset that is being used?

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Findings:
- It can be seen from the visualising the training results that the Training accuracy is increasing with the number of epochs, but, the validation accuracy is randomly increasing and decreasing. Also, the difference between training accuracy and validation accuracy is very huge.

The training loss is decreasing with a big gap for first 2 epochs and after that there is a gradual decrease as epochs increase. The validation loss increase and decrease randomly

So, we can say that our model is Overfitting.


## Conclusions:
* We have built a decent model which is free of overfitting and has good enough accuracy on training as well as validation sets.


## Technologies Used
- pathlib
- tensorflow
- matplotlib.pyplot
- numpy
- pandas
- os
- PIL
-keras (layers / sequential)







## Contact
Created by [@maheeprajgupta] - feel free to contact me!

