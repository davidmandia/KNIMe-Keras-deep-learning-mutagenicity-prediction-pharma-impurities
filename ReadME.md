# AI mutagenicity prediction 


This project was part of my final year project.
The intent of developing computational methods to predict mutagenicity in drug impurities 

![Project Logo](./images/project-logo.png)

## Features

### Binary Classification in Keras
I have used multi layer keras nodes. The hyperparameter were tested and optimised. The final setting is hidden 2 layers with 100 and 50 neurons respectively.
The chosen activation function was Tanh, and the loss was SGD

## Installation
The folder "model" contains the Knime Workflow to be downloaded and imported on Knime
"data" contains the training and external validation set. The model includes some nodes to implement a left join on external validation.
This was done to ensure no data in the external validation was present in the training set give the fact that the trainig data set was made of various databases

## Usage

Instructions for usage.

## Model 

