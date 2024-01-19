# Plant Disease Classification using PyTorch

This repository contains the implementation of a plant disease classification model using PyTorch. The model is based on a fine-tuned ResNet-18 architecture for image classification tasks of the plantvillage dataset.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Model Saving](#model-saving)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to classify plant diseases based on images. The model is implemented in PyTorch and utilizes data augmentation and a pre-trained ResNet-18 model for improved accuracy.

## Dataset

The dataset used for this project is available [here](https://www.kaggle.com/datasets/emmarex/plantdisease). It consists of images of plants affected by various diseases. The dataset is organized into different classes based on the type of disease.The dataset is available for download at kaggle, dataset name Plantvillage dataset

## Installation

To install and run this pytorch model follow the following steps.

1.) open the notebook on google colab.
2.)

## Usage

1. Ensure the dataset is downloaded and organized in the specified structure.
2. Modify the `config cell`  to set the dataset path and other configurations.
3. Run the training script on the training cell:

4. Evaluate the model on the evaluation cell

## Training

The model is trained using a fine-tuned ResNet-18 architecture. Data augmentation techniques are applied to enhance the model's robustness. The training script (`train cell`) contains the main training loop.

## Evaluation

The model is evaluated on a separate test set to measure its accuracy and performance. The evaluation script cell (`evaluate cell`) computes the accuracy and validation loss.

## Results

The trained model achieves an accuracy of approximately 51% on the test set. Further details can be found in the `Results` section of the code.

## Model Saving

The trained model is saved using `torch.save` and can be loaded for future use. The saved model file (`fine_tuned_resnet18.pth`) contains the model's state dictionary.

## Customization

Feel free to customize the code, experiment with hyperparameters, or try different pre-trained models for improved performance. You can also contribute by adding new features or enhancing existing ones.

## Contributing

Contributions are welcome, i humbly request for a collaboration on this notebook for an improvement on the accuracy! Feel free to open issues, submit pull requests, or provide feedback.

## License

This project is licensed under the [MIT_license](MIT_license).
