# Melanoma-assignment

# Skin Cancer Detection using CNN

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
This project aims to build a Convolutional Neural Network (CNN) model for accurate melanoma detection. Melanoma, a deadly form of skin cancer, is responsible for 75% of skin cancer deaths. Early detection is crucial for effective treatment. This project automates the evaluation of skin images, alerting dermatologists to potential melanoma cases, reducing manual effort and improving diagnosis speed.

**Business Problem:**  The project addresses the need for efficient and accurate melanoma detection to improve patient outcomes. Early diagnosis significantly increases the chances of successful treatment.

**Dataset:** The project utilizes a dataset of approximately 2357 images of various skin cancer types, categorized into 9 sub-directories for training and testing. These sub-directories represent 9 distinct skin cancer types.

## Conclusions
- The initial CNN model exhibited overfitting, indicating the need for data augmentation and regularization techniques.
- Data augmentation, using techniques like rotation and shifting, was employed to address overfitting and enhance model generalization.
- Dropout layers were incorporated into the model architecture to further mitigate overfitting and improve performance.
- Class imbalance was identified and addressed through augmentation, leading to a more balanced dataset and enhanced model training.
- The final model, after data augmentation and regularization, demonstrated improved performance and reduced overfitting.

## Technologies Used
- tensorflow - 2.13.0
- matplotlib.pyplot - 3.7.1
- numpy - 1.25.2
- pandas - 1.5.3
- Augmentor - 1.5.0

## Acknowledgements
- This project was inspired by the need for automated skin cancer detection.
- References: towardsdatascience.com, augmentor.readthedocs.io


## Contact
Created by [sindhuperi2693] - feel free to contact me!
