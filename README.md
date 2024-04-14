# meter-reader-ai-model
This repository contains code and instructions for training an Object Detection model using Amazon SageMaker.

## Setup
### Requirements
- Amazon SageMaker
- Dataset 

### Installation
- Download notebooks under `notebook` dir 
- update to `sagemaker studio` `jupyter server` 

### Dataset Preparation
- Upload the dataset
- run `DETR_meter_reading_prep_v0.ipynb` notebook 

## Training
### Training on SageMaker
- run `DETR_meter_reading_train_v0.ipynb` notebook
- download the trained weights from `checkpoint` dir

### Hyperparameter Tuning
- In progress ...

## Evaluation
### Model Evaluation
- In progress ...

## Deployment
### Deployment Script
- rename the model weights file according to documentations
- Upload the trained model weights to `s3:meter-reading-model` 

## Usage
### Inference
- run `DETR_meter_reading_test_v0.ipynb` notebook

## Contributing
1. Create a new branch (git checkout -b feature-branch).
2. Make your changes and commit them (git commit -am 'Add new feature').
3. Push to the branch (git push origin feature-branch).
4. Create a new Pull Request.