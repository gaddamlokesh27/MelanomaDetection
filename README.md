# Project Name
> * Assignment : Melonoma cancer detection assignment
> * Team Member :  Lokesh Gaddam
> * Date : 18Sep2024
 
 
## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
 
 
## General Information
> ### Business Understanding :
> Skin cancer encompasses over 200 different forms, with melanoma recognized as the most lethal type. The diagnostic pathway for melanoma involves initial clinical screening followed by dermoscopic analysis and histopathological examination. Early detection is critical for successful treatment, as melanoma is highly curable when identified at its initial stages.

> The first step in diagnosing melanoma involves visually examining the affected skin area. Dermatologists use high-speed cameras to capture dermatoscopic images of skin lesions. These images typically yield an accuracy of 65-80% in melanoma diagnosis without additional technical assistance. When supplemented with further visual examination by cancer specialists and dermatoscopic images, the overall prediction accuracy for melanoma diagnosis can increase to 75-84%.

> This project aims to develop an automated classification system leveraging image processing techniques to classify skin cancer based on skin lesion images. The goal is to create a reliable and efficient tool that can assist in the early detection and diagnosis of melanoma and other skin cancers using advanced computational methods and image analysis.
## Problem statement
>> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
 
## Steps followed 
> Importing Skin Cancer Data
> Importing all the important libraries
> Load using keras.preprocessing
> Create a dataset
> Visualize the data
> Create the model
> Compile the model
> Train the model
> Visualizing training results
> Compiling the model
> Training the model
> Visualizing the results

## Conclusions
> ### EDA Summary 
>Conclusion Summary:
> - After incorporating the Augmentor library to generate additional samples, we observed an improvement in training data accuracy. However, the model continues to exhibit signs of overfitting.

> - To mitigate overfitting, we can explore several strategies such as adding more layers or neurons to the model, or incorporating dropout layers to promote generalization by preventing the model from relying too heavily on specific features.

> - Furthermore, enhancing model performance can be achieved by fine-tuning hyperparameters such as learning rate, batch size, optimizer choice, and regularization strength. This iterative tuning process aims to optimize the model's architecture and training configuration for better generalization and performance on unseen data.
 
## Technologies Used
> - Goggle collab for scalable compute units and GPUs 
> - Jupyter note book v2.5.0
> - python3 & necesary libraries for statistics, deep learning , visualization and modeling 
 
 

 
