# Skin Cancer prediction model using CNN
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
                    1. Model 1: Base Model - CNN                : Training Accuracy = 90 %   & Validation Accuracy = 50 % 
                    2. Model 2: Model with Augmentation Epoch=20: Training Accuracy = 90 %   & Validation Accuracy = 83 %
                    3. Model 3: Model with Augmentation Epoch=30: Training Accuracy = 92 %   & Validation Accuracy = 85 %
                    4. Based on results Model 1 had overfitting issue , which was resolved after augmentation. 
                    5. Model 2 gave better accuracy in terms of validation, which proves overfitting issue is solved.
                    6. Model 3 provided better accuracy, however it does not improve much considering compuation efforts (Epochs 20 vs 30)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python
Keras
CNN

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@AbhijitWableAI] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->