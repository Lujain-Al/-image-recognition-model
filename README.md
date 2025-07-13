# -image-recognition-model
# Image Recognition Model Project Using Teachable Machine

This project aims to train an image recognition model using Google’s Teachable Machine. The model is designed to classify two types of flowers: roses and tulips.

## Requirements

- Python 3.x
- TensorFlow library
- PIL (Pillow) library

## Steps

### 1. Image Preparation

- Used 7 images of roses and 7 images of tulips.
- Organized the images into separate folders for each type:
  - `roses/`
  - `tulips/`

### 2. Model Training

- Utilized [Teachable Machine] to train the model.
- Uploaded the images and trained the model using the Teachable Machine interface.
- Tested the model with one image from each type.

### 3. Model Download

- Downloaded the model in TensorFlow → Keras format.

### 4. Python Script

- A Python script was written to load the model and predict the class of an image. You can find the script in the file `predict.py`.
