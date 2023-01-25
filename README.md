# melanoma-prediction

In this repository, we aim to build a CNN based model which can detect melanoma. The object of the project is to undertand development of a CNN model using Keras and understand various strategies that will come up when building neural networks, including solving for underfitting, overfitting and class imbalance.  

## Project Pipeline
**Data Reading/Data Understanding** → Defining the path for train and test images

**Dataset Creation**→ Create train & validation dataset from the train directory with a batch size of 32 and image size of 180*180

**Dataset visualisation** → Create a code to visualize one instance of all the nine classes

**Model Building & training**
- Create a CNN model, which can accurately detect 9 classes present in the dataset.

**Chose an appropriate data augmentation strategy to resolve underfitting/overfitting if present** 

**Model Building & training on the augmented data** :
- Create a CNN model, which can accurately detect 9 classes present in the dataset. 
- Findings after the model fit to identify if the model is still under or overfit.

**Class distribution: Examining the class distribution in the dataset** 

**Handling class imbalances**: Using the Augmentor library to increase the number of sample images for specific classes by augmenting data.

**Model Building & training on the rectified class imbalance data** :
- Create a CNN model, which can accurately detect 9 classes.
- Findings after model fit to identify whether or not our strategies have helped to increase the performance of the model.

## Technologies Used
- pathlib
- matplotlib
- numpy 
- pandas 
- os
- PIL
- tensorflow
- keras
- glob


## Contact
Created by [@justinhtn]
