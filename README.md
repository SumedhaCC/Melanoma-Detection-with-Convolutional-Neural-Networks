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

