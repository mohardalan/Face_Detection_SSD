# Face Detection using Single Shot Detector (SSD)

This project aims to develop two face detection models using the Single Shot Detector (SSD) approach. The SSD model comprises two key components: the Generator and Discriminator models, which are responsible for distinguishing between faces of the same and different individuals.

## Models Overview

- **Model 1: CNN-based Generator**
  - Utilizes Convolutional Neural Network (CNN) layers within the Generator model to extract features from input face images.
  
- **Model 2: VGG19-based Generator**
  - Utilizes a pre-trained VGG19 model for feature extraction.

## Dataset

The input dataset consists of multiple images of famous individuals, which are used to create pairs of images representing the same and different people. Proper labels are assigned based on whether the images depict the same person or not. These image pairs are utilized for training, validation, and testing of the models.

## Training
The models are trained using the created dataset. The training process involves loading and preprocessing the images, defining the model architecture, compiling the model, and fitting it to the training data.

## Evaluation and Testing
The trained models are evaluated using the test set to assess their performance. Metrics such as accuracy, F1 score, and a classification report are used to evaluate the models' performance.

## Real-time Face Detection Application
To apply the trained models, a new model is developed to capture a new image of a person using a webcam and compare it with pre-defined images of known individuals. This real-time application demonstrates the practical use of the trained models for face detection.

## Results
Despite limitations in time and hardware resources, both models demonstrate acceptable performance in terms of accuracy and F1 score.

## Real-time Face Detection

To apply the trained models, a new model is developed. This model captures a new image of a person using a webcam and compares it with pre-defined images of known individuals. This way, the model trained in the previous step serves as an application for real-time people detection.

## Usage

Train the models using the provided dataset.
Run the real-time face detection application using a webcam.


Feel free to customize this template according to your project's specific details and structure!

