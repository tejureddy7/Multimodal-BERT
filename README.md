README.md
-------------------------

This folder contains artifacts related to the final project submission of Vineeth NC and Tejaswini Manjunath for CMSC 473/673 — Introduction to Natural Language Processing. The project is based on Training Vision-Language Models for Image Classification.

The artifact directory structure is as follows:

* CODE
  * BERT_LSTM.ipynb
  * InceptionV3.ipynb
  * Final_Stacking_Late_Fusion.ipynb 
* DATASET
  * RGB_Cropped
  * stratified_datase
* MODELS
  * Text+Image.hdf5
  * InceptionV3_weights.hdf5
  * BERT+LSTM_weights.hdf5

* RESULTS
  * Graphs
  * Data



CODE
-------------------------
Contains different codes that are used for the project.

BERT_LSTM.ipynb is a Jupyter notebook that can be used to train the text only model BERT+LSTM. The dataset used to train this model is in the directory Dataset\stratified_dataset\. 

InceptionV3.ipynb is Jupyter notebook file used to train the image CNN model. The same dataset as previous is used to train this model.

Final_Stacking_Late_Fusion.ipynb is the ipynb file used to train image and text models. The Dataset in Stratifiedd_dataset folder or the dataset in RGB_Cropped folder can be usedd to train this model by changing the paths in the code.


Specific instructions are written in the file.


DATASET
-------------------------
This folder contain datasets to be used for training all the models.
"stratified_dataset" - contains train, test and validation image folders as well as train, test and validation tsv text files.
"RGB_Cropped" - contains only the train, test and validation image folders just split in a different way.



MODELS
-------------------------
Contains the weights of all three different models used to train. They are named accordingly.



RESULTS
-------------------------

This folder contains all the images and data used to generate the images.# Multimodal-BERT
