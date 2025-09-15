# Computer Vision Project: CIFAR-10 Image Classification

This project implements an advanced Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset. The project pipeline includes data loading, exploration, model definition, training, evaluation, and results analysis.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Project Structure](#project-structure)
- [Setup and Installation](#setup-and-installation)
- [Running the Project](#running-the-project)
- [Results and Analysis](#results-and-analysis)
- [Files](#files)

## Introduction

This project aims to classify images from the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The task is to train a model that can accurately predict the class of a given image.

## Dataset

The project uses the CIFAR-10 dataset. The `DatasetExplorer` class handles loading and preprocessing the dataset, including data augmentation techniques like random cropping and horizontal flipping. Normalization is applied using the mean and standard deviation of the CIFAR-10 dataset.

## Model Architecture

The model used is an `AdvancedCNN`, a custom Convolutional Neural Network architecture. It consists of multiple convolutional layers with batch normalization and ReLU activation, followed by max pooling layers. The network ends with fully connected layers and dropout for regularization.

## Project Structure

The project is organized into several classes:

- `DatasetExplorer`: Handles dataset loading, preprocessing, and visualization.
- `AdvancedCNN`: Defines the architecture of the CNN model.
- `ModelTrainer`: Manages the training and evaluation loops, including optimizer, loss function, and learning rate scheduling.
- `ResultsAnalyzer`: Provides functions for visualizing training curves, plotting confusion matrices, generating classification reports, and showing sample predictions.


