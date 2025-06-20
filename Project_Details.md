# Prerequisites To Implement this Project

1. Python Programming (OOPs Concept Required)
2. Machine Learning and Deep Learning - Object Classification Basic & Tensorflow 2.x API
3. MLflow, DVC, AWS

# Major Steps in Kidney Disease Classification using MLflow & DVC

0. General Instruction
1. Introduction & GitHub Repository Setup
2. Project Template Creation
3. Project Setup & Requirements Installation
4. Logging, Utils & Exception
5. Project Workflows
6. All Components Notebook Experiment
7. All Components Modular Code Implementation
8. Training Pipeline
9. MLflow (MLOps Tool) - For Experiment tracking & Mode Registration
10. DVC (MLOps Tool) - For Pipeline Training & Implementation
11. Prediction Pipeline & User App Creation
12. Docker
13. Final CI/CD Deployment on AWS

## Section 0 General Instructions

1. To commit changes made locally in the github repository type the following set of commands
    
    ```bash
    git add .
    ```
    ```bash
    git commit -m "Message that you want to print"
    ```
    ```
    git push origin main
    ```

2. You can perform these same operations in vs code using the source control tab where in the message box you type the Message that you want to print and then click on the commit button after which you need to click on the sync button to synchronise change at both ends

## Section 1 Introduction & GitHub Repository Setup

Kidney tumours (also called renal tumors) are growth in the kidneys that can be benign or cancerous. Most do not cause symptoms and are discovered unexpectedly when you are being diagnosed and treated for another condition.

![Normal vs Tumor](Images\1.png)

GitHub Repository Setup Steps

1. Login to your github account and then click on create a new repository
2. Provide a valid name to the repository and click on add a README file.
3. Click on create repository
4. Copy the link to the github repository from the code download section.
5. Open the folder where you want to create this project folder with any terminal (GitBash/ Terminal/ Anaconda Promt) and type this command given below and you will see that entire project folder is copied at the desired location. 
    ```bash 
    git clone https://github.com/Krushang-kadakia/Kidney-Disease-Classification-.git 
    ``` 
6. Navigate to the project folder using the following command in the terminal 
    ```bash
    cd Kidney-Disease-Classification-
    ```
7. To open the code editor type the following command in the terminal
    ```bash
    code .
    ```

## Section 2 Project Template Creation

Create a template.py file inside the project folder and create the project template.

1. Import packages like os, pathlib and logging to create the entire project structure and create a log the work done.
2. Create a logging string because when we execute this template.py file so the work done by the code or changes made need to be logged instead of printing them. It is a good practice to use log statement instead of a print statement
3. Create a list of files with their specified location inside a folder 
4. Using the path class from the pathlib module convert every item in the list of files as a file path.
5. Create the folders and files using the os module and log the changes
6. Execute the template.py file uisng the following command in the terminal 
    ```bash
    python template.py
    ```

## Section 3 Project Setup & Requirements Installation
<<<<<<< HEAD

1. In the requirement file list down the dependencies with the version where ever required. Some of the examples are gdown to read data from the google drive and -e . is used to install the current directory in editable mode as a local package 
2. Create the setup.py file by providing the personal details 
3. Create a virtual environment of python version 3.10 using the following command
    ```bash
    py -3.10 -m venv <env_name>
    ```
4. Activate the environtment using the following command
    ```bash
    .\<env_name>\Scripts\Activate.ps1
    ```
5. Install the dependency in the virtual environment using the below command
    ```bash
    pip install -r requirements.txt
    ```
6. To decativate the environment just type the folowing command in the terminal
    ```bash
    deactivate
    ```
    
=======
>>>>>>> 9e4e193961b093fe8009d04a62daecfae7e53af9
