# Brain-Tumor-Classifier
A Multi-Class Brain Tumor Classifier using Convolutional Neural Network with 99% Accuracy achieved by applying the method of Transfer Learning using Python and Pytorch Deep Learning Framework.
NeuralBlack is a complete brain tumor detection, classification, and diagnosis system with high accuracy (99.3%) that uses state of the art Deep Learning methods.

This brain tumor dataset containing 3064 T1-weighted contrast-inhanced images from 233 patients with three kinds of brain tumor: meningioma (708 slices), glioma (1426 slices), and pituitary tumor (930 slices).

# Modules
brain_tumor_dataset_preparation.ipynb - An IPython notebook that contains preparation and preprocessing of dataset for training, validation and testing.

torch_brain_tumor_classifier.ipynb - An IPython notebook that contains all the steps, processes and results of training, validating and testing our brain tumor classifier.

test.py - A python script which accepts path to an image as input, which then classifies the image into one of the three classes.

deploy.py - A python script integrated with Flask server, that starts the Web Interface on local server where user can upload MRI image of brain and get classification results.

# Running the classifier
Download the classifier model '.pt' file from this drive link(https://drive.google.com/file/d/1-rIrzzqpsSg80QG175hjEPv9ilnSHmqK/view?usp=sharing) and place it under a folder named 'models' in the same directory where the files of this repository are present.

Before running the programs, kindly install the requirements as given in Requirements section of this README.

Use the test.py script for running the script in Terminal, Powershell or Command Prompt.
python test.py

Use deploy.py script to access the classifier as an interactive web interface.
python deploy.py

# Library Requirements
We'll be using the following libraries to complete our classification problem:

Numpy - For linear algebra operations

Torch - Pytorch Deep Learning Framework

OS - To use Operating System methods

Random - To set random seed at specific places where random operations take place just so it happens the same way everytime it is executed

Pandas - To create DataFrame, CSV files, etc

Time - To perform date time operations

Seaborn - For sophisticated visualization

Pickle - To save and load binary files of our training data

Scikit-Learn - Machine learning framework. We have used this for evaluating our Classifier and for cross-validation split

Matplotlib - To visualize images, losses and accuracy

# References : Akshay Kumaar M (aksh-ai on github)
