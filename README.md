# ZhMed

This repository contains code and resources for training and evaluating Named Entity Recognition (NER) models for Chinese medical texts. The purpose of this README is to provide an overview of the key files and functionalities included in the repository.  

# Dataset Concatenation File
 • datasets_concatenation.ipynb: This script is used to concatenate multiple datasets into a single dataset file. It takes individual dataset files in a specific format and merges them into a combined dataset file. The combined dataset file can then be used for training and evaluation purposes.  
# Training and Evaluation
 • TRAINING.ipynb: It outlines the necessary steps for preparing the data, configuring the model, and initiating the training process. The notebook serves as a comprehensive reference for users who want to train their own models using the provided codebase.After training, the script evaluates the trained models on the test dataset and reports performance metrics such as precision, recall, and F1 score.  
  • train.py: This file serves as the main training script for NER models. It has been modernized from the CBLUE benchmark to ensure a proper evaluation process. The script supports various configurable options, including model architecture, hyperparameters, and training settings.   

# Train-Test-Dev Datasets
 • CMeEE_train.json: This file contains the training dataset for NER model training. It consists of Chinese medical texts annotated with named entities.  
 
 • CMeEE_test.json: This file contains the test dataset for evaluating the trained NER models. It includes Chinese medical texts with annotated named entities that are used to measure the model's performance.  
 
 • CMeEE_dev.json: This file contains the validation dataset used for tuning hyperparameters and monitoring the model's progress during training.  

