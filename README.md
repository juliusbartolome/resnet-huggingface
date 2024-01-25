# ResNet-50 Image Classification and Object Detection

## Introduction

This project is an exploration of image classification and object detection using ResNet-50, a popular Convolutional Neural Network (CNN) model. We will be comparing the implementations provided by two major tech companies: Facebook and Microsoft.

## Setup

To set up the project, follow these steps:

1. Create the conda environment:

    ```bash
    conda env create -f env.yml
    ```

2. Set the Hugging Face API key:

    ```bash
    conda env config vars set -n restnet50-huggingface HUGGINGFACE_API_KEY=redacted
    ```

3. Activate the conda environment:

    ```bash
    conda activate restnet50-huggingface
    ```

4. Start the Jupyter notebook:

    ```bash
    jupyter notebook
    ```

## Image Classification

### Facebook's Implementation

In this section, we will be using Facebook's implementation of ResNet-50 for image classification. We will train the model on a dataset of images and evaluate its performance in accurately classifying those images.

### Microsoft's Implementation

In this section, we will be using Microsoft's implementation of ResNet-50 for image classification. We will train the model on a dataset of images and evaluate its performance in accurately classifying those images.

## Object Detection

In addition to image classification, we will also explore object detection using ResNet-50. This involves not only classifying what objects are present in an image, but also identifying their locations.

## Notebook

The `resnet50-huggingface.ipynb` notebook contains all the code and detailed explanations for the project. You can run the notebook to train the models and see the results.