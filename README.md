# COVID-19 Image Classification with DenseNet121

## Overview

This project demonstrates how to use the DenseNet121 model to classify images related to COVID-19. The model is trained to differentiate between images of different categories related to COVID-19. The workflow includes downloading a dataset, preparing the data, building and training a model, and evaluating its performance.


## Purpose

The primary goal of this project is to provide a solution for classifying COVID-19 related images. This tool can be adapted for other image classification tasks by modifying the dataset and labels.

## Features

- **Pre-trained DenseNet121**: Utilizes DenseNet121 with ImageNet weights for feature extraction.
- **Data Augmentation**: Implements data augmentation techniques to improve model robustness.
- **Model Training and Evaluation**: Trains the model and evaluates its performance using loss and accuracy metrics.

## Dataset

The dataset used in this project contains images related to COVID-19, which are organized into training and validation directories.


## Final Model Performance

Test Loss: 0.0292

Test Accuracy: 96.67%


![download](https://github.com/user-attachments/assets/952b848e-d91e-4634-b95d-ae83ec4dc88e)



### Download and Unzip Dataset

```bash
# Download the dataset
!wget http://cb.lk/covid_19

# Unzip the downloaded dataset
!unzip covid_19
