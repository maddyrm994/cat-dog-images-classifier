# Cat-Dog Images Classifier

This repository contains a Jupyter notebook that implements a Convolutional Neural Network (CNN) to classify images of cats and dogs using the ResNet-50 architecture.

## Dataset

The dataset used for this project is the "Dogs vs. Cats Redux" dataset from Kaggle. It contains images of cats and dogs that are used to train and test the classifier.

## Notebook Overview

The notebook performs the following tasks:
1. Imports necessary libraries.
2. Defines constants and paths.
3. Extracts the dataset from the provided zip files.
4. Processes and prepares the data for training and testing.
5. Visualizes the distribution of the dataset.
6. Defines the CNN model using the ResNet-50 architecture.
7. Compiles and trains the model.
8. Evaluates the model's performance on the validation set.
9. Generates predictions for the test set.
10. Creates a submission file for Kaggle.

## Model Architecture

The model uses the ResNet-50 architecture with the following layers:
- ResNet50 (pre-trained on ImageNet, without the top layer)
- Dense layer with softmax activation for classification

## How to Use

1. Clone the repository:
   ```
   git clone https://github.com/maddyrm994/cat-dog-images-classifier.git
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Download the dataset from Kaggle and place the zip files in the appropriate directory.
4. Run the Jupyter notebook:
   ```
   jupyter notebook cats-vs-dogs-images-classifier.ipynb
   ```
