# SVM Cats vs Dogs Classifier

## Project Overview
This project implements a Support Vector Machine (SVM) classifier to distinguish between images of cats and dogs. Utilizing machine learning at its core, this model aims to provide a robust solution for image classification tasks within the pet domain.

## Features
- **Image Preprocessing**: Automated preprocessing pipeline for images to enhance classifier performance.
- **SVM Model**: Implementation of the SVM algorithm with hyperparameter tuning for optimal results.
- **Model Evaluation**: Comprehensive evaluation reports including accuracy, precision, recall, and confusion matrices.
- **User-Friendly Interface**: A straightforward command line interface for model interaction and evaluation.

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Scikit-Learn
- OpenCV
- Matplotlib
- TensorFlow (if applicable)

## Usage Instructions
1. Clone the repository:  
   `git clone https://github.com/daryahussain/CODECRAFT_ML_03.git`
2. Navigate to the project directory:  
   `cd CODECRAFT_ML_03`
3. Install the required dependencies:  
   `pip install -r requirements.txt`
4. Prepare your dataset and place it in the appropriate directory.
5. To train the model, run:  
   `python train.py`
6. To test the model, use:  
   `python test.py`

## Model Details
The model is built using the Scikit-Learn library, leveraging the SVM algorithm. Key parameters include:
- **Kernel Type**: RBF
- **C**: Regularization parameter
- **Gamma**: Kernel coefficient

The trained model can also be saved and loaded for future use, optimizing the workflow of image classification tasks.