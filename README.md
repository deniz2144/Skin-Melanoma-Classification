# Skin-Melanoma-Classification
 Skin Melanoma Classification using CNN 



File 1: Step01-Prepare-The-Data.py

Purpose: In the processing of skin parts; resizing and converting to grayscale.
Process: Reads in tags from the CSV file, processes the details, and connects the results to NumPy arrays.


File 2: Step02-Build-CNN-Model

Process:
Bu adımın amacı, önceden işlenmiş cilt lezyonları verilerini kullanarak bir sinir ağı modelini eğitmek ve modelin performansını değerlendirmektir. Bu süreç, modelin belirli cilt lezyonu türlerini sınıflandırma yeteneğini ölçmeyi ve doğruluğunu artırmayı hedefler.

Purpose:
The purpose of this step is to train a convolutional neural network (CNN) model using preprocessed skin lesion data and to evaluate the performance of the trained model. This involves loading image and label data, preparing it for model training, defining and training the model, and finally assessing the model's accuracy and loss on test data. The goal is to optimize the model’s performance in classifying skin lesions into specified categories.

![. 2024-07-23 180459](https://github.com/user-attachments/assets/ca5850ee-0b36-4261-a1b1-1d26ef28be2f)




![. 2024-07-23 180406](https://github.com/user-attachments/assets/471e34e8-e86b-4872-b146-31796cae2f23)




File 3:Step03-Test-The-Model
(Purpose):
This step involves loading the pre-trained model and image pre-processing so that a particular image is processed by the model. This process performs the necessary preprocessing for the model to make predictions on new images and displays summary information to check the structure of the model.



