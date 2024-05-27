# Machine Learning Handwritten Digit Recognition Project

## Description:

This is my machine learning capstone project for Western Governors University. The project focuses on developing 
a classification model capable of recognizing handwritten digits. Using the MNIST public dataset, the model has 
been trained to take an input image of a handwritten digit and accurately predict the corresponding number.

## Key Features:

- Dataset: Utilizes the MNIST public dataset, which contains 60,000 training images and 10,000 testing images of handwritten digits (0-9).
    
- Model: Implements a machine learning classification model using scikit-learn and KNN algorithm.

## Tools and Libraries:

- scikit-learn for building and evaluating the model
- numpy and pandas for data manipulation
- matplotlib for data visualization
- Jupyter Notebook for project development

## Installation and User Guide

### Installing Miniconda

Go to the Miniconda installer page.
Click to install the Python 3.12 version
Follow the installation process 

### Cloning the Project Repository

Open your web browser and go to the GitHub repository for this project: 

      https://github.com/Joh221105/ml-handwritten-digit-recognition/tree/main

Click the "Code" button and copy the URL provided.

### Setting Up the Project

Open Anaconda Prompt (Miniconda3)
Clone the project into desired directory
Navigating to the Project Directory

### Creating a Virtual Environment

Create a new virtual environment and install the necessary dependencies by typing the following command
    
    conda create --prefix ./env pandas numpy matplotlib scikit-learn jupyter -y
    
Activate the environment: 
  
    conda activate ./env
    
### Running the Jupyter Notebook

Start Jupyter Notebook by typing:

    jupyter notebook

### Using the Application

Open the application.ipynb 
Run the first two cells
Go to the cell under "User Uploaded Input and Prediction"
Provide the path to the image you want to predict to uploaded_image = Image.open(" ")
Run the cell to get the prediction

