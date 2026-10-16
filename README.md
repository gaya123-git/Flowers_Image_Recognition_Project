# Flower Image Recognition

## Overview
This project explores image classification using deep learning to identify five types of flowers: daisies, dandelions, roses, sunflowers and tulips.

## Current Progress
- Loaded and explored the TensorFlow Flowers dataset.
- Resized and batched images for model training.
- Used transfer learning with a pretrained MobileNetV3Small model.
- Added a custom classification head for five flower classes.
- Trained the model and monitored training and validation performance.
- Implemented Softmax-based predictions to estimate class probabilities.

## Planned Improvements
- Introduce separate training, validation and test datasets.
- Improve training using callbacks and model checkpointing.
- Evaluate test accuracy, loss and top-3 accuracy.
- Analyse classification errors using a confusion matrix and classification report.
- Display the top three predicted flower classes with confidence scores.
- Save the trained model for future application integration.
- Expand the dataset with additional self-collected flower and plant images to improve model testing and validation in future iterations.

## Technologies
- Python
- TensorFlow / Keras
- TensorFlow Datasets
- NumPy
- Matplotlib

## Project Status
In progress — currently developing and evaluating the flower classification model
