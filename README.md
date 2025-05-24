# Dogs vs. Pastries: Neural Network Image Classifier

This repository contains a project completed during the *Machine Learning* course of my Master’s in Data Science and Economics. The objective was to build and optimize a convolutional neural network (CNN) capable of distinguishing between images of Chihuahuas and muffins - a classic example of challenging image classification.

## Repository Contents

- `ml-project.ipynb`: Jupyter Notebook with all code and experiments
- `ML PROJECT.pdf`: Final project report (PDF format)
- `README.md`: Overview and documentation
- `ML PROJECT.pages`: Original report (Apple Pages format)
  
### Project Setup

- Loaded and preprocessed the dataset (training and testing)
- Defined helper functions for image loading and transformation
- Used `ImageDataGenerator` to apply **data augmentation**
- Split augmented images into **training and validation** sets
- Experimented with different model setups
- Fine-Tuning & Optimization: used Keras Tuner (Hyperband) to tune the hyperparameters
