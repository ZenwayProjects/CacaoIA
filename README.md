# Cocoa Maturity Detection Algorithm

This repository contains the implementation of a cocoa maturity detection algorithm using a deep learning model. The algorithm takes cocoa images as input and predicts their maturity levels. The model is designed to classify cocoa images into different categories: cocoaI, cocoaM, cocoaS, and notcocoa.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Data Preprocessing](#data-preprocessing)
- [Training](#training)
- [Evaluation](#evaluation)
- [Usage](#usage)
- [Contributions](#contributions)

## Introduction

Cocoa maturity detection is an important aspect in cocoa production. This algorithm leverages deep learning techniques to automatically classify cocoa images into different maturity levels, which can assist farmers and experts in assessing the state of cocoa pods.

## Dataset

The dataset used for training and evaluation is available in the `dataset_cacao` directory. It consists of categorized images in training and testing sets. The dataset includes various maturity levels and a "notcocoa" class for non-cocoa images.

## Model Architecture

The architecture of the deep learning model used for cocoa maturity detection is a custom-designed architecture tailored to handle image classification tasks.

## Data Preprocessing

Images are preprocessed using techniques such as resizing, data augmentation, and scaling of pixel values.

## Training

The model is trained using the training dataset and validated using the validation dataset.

## Evaluation

The trained model is evaluated on the test dataset to assess its performance.

## Usage

1. Clone this repository.

2. Place your cocoa images in the `dataset_cacao/Testing` and `dataset_cacao/Training` directories.

3. Run the prediction script: from Colab environment for added convenience.

## Contributions

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, open an issue or submit a pull request.
