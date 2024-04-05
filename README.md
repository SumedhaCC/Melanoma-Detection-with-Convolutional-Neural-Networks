# Melanoma-Detection-with-Convolutional-Neural-Networks
This project aims to build a custom CNN model in TensorFlow to accurately detect melanoma, a deadly form of skin cancer. Early detection is crucial, and this model can potentially assist dermatologists by evaluating images and alerting them to possible melanoma presence.
Dataset
The dataset consists of 2357 images of various skin conditions downloaded from the International Skin Imaging Collaboration (ISIC). It includes images of:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion
Project Pipeline
Data Reading/Understanding:

Define paths for training and testing images.
Dataset Creation:

Create training and validation datasets from the training directory with a batch size of 32.
Resize images to 180x180 pixels.
Dataset Visualization:

Visualize one image from each of the nine classes.
Model Building & Training (Original Data):

Create a CNN model to classify the nine classes.
Rescale images to normalize pixel values between 0 and 1.
Choose an appropriate optimizer and loss function.
Train the model for 20 epochs.
Analyze results for overfitting or underfitting.
Model Building & Training (Augmented Data):

Implement data augmentation techniques to address overfitting/underfitting.
Repeat steps 4.1 - 4.4 with the augmented data.
Analyze results for improvement in overfitting/underfitting.
Class Distribution:

Examine the distribution of samples across each class in the training dataset.
Identify classes with the least and most data.
Handling Class Imbalances:

Use the Augmentor library to rectify class imbalances.
Model Building & Training (Balanced Data):

Repeat steps 4.1 - 4.4 with the class-balanced data.
Train for 30 epochs.
Analyze results for improvement due to balanced classes.
