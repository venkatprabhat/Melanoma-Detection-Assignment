# Melanoma Skin Cancer Detection

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
Melanoma is the deadliest form of skin cancer, and early detection significantly improves survival rates. Current diagnostic procedures include clinical screening, dermoscopic analysis, and histopathological examination. Dermatologists rely on dermatoscopic images with a diagnostic accuracy of 65-80% without additional technical support, which improves to 75-84% with further expert visual examination.

This project aims to develop an automated classification system using image processing and deep learning to classify skin lesions. The predictive model will help reduce the current diagnostic timeline from over a week to just a few days, potentially benefiting millions of individuals.

**Business Problem:**
The conventional skin biopsy process is time-consuming, requiring dermatologist appointments and microscopic examination. This project seeks to reduce this duration significantly by leveraging Convolutional Neural Networks (CNNs) to classify nine types of skin lesions.

**Dataset:**
The dataset, sourced from the International Skin Imaging Collaboration (ISIC), contains 2,357 images of both malignant and benign oncological diseases. Data augmentation techniques using the Python Augmentor library were applied to address class imbalance.


## Conclusions
- An automated CNN-based system can significantly reduce diagnostic times for melanoma detection.
- Image processing techniques improve classification accuracy for skin lesions.
- The developed model efficiently classifies nine types of skin cancer.
- Early diagnosis and faster detection can lead to better treatment outcomes and reduced mortality rates.

## Technologies Used
- Python 3.x
- TensorFlow 2.x
- Keras
- Augmentor (for data augmentation)
- NumPy, Pandas, Matplotlib, Seaborn

## Acknowledgements
- Inspired by the American Cancer Society’s resources on melanoma skin cancer.
- CNN and image classification references from Analytics Vidhya.
- CNN architecture guidance from Towards Data Science.

## Contact
Created by [@ViswanadhaVenkatPrabhat] - feel free to contact me for questions or collaborations!

