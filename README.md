# Human Expressions Recognition Project

## Introduction
This project aims to recognize human facial expressions using a Convolutional Neural Network (CNN). The dataset consists of images categorized into seven emotions: angry, disgust, fear, happy, sad, surprise, and neutral.

## Project Structure
- `human_expressions.ipynb`: Jupyter notebook containing the full project code, including data loading, preprocessing, model training, and evaluation.
- `requirements.txt`: List of required packages to run the project.
- `README.md`: Project documentation and instructions.

## Dataset
The dataset used in this project is divided into training and testing sets, each containing images of faces categorized into seven emotions: angry, disgust, fear, happy, sad, surprise, and neutral.

## Installation
1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```bash
    cd <repository-directory>
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open the Jupyter notebook:
    ```bash
    jupyter notebook human_expressions.ipynb
    ```
2. Run the cells in the notebook to execute the code.

## Project Details

### Data Loading and Preprocessing
The dataset is loaded and preprocessed to fit the model requirements. The images are resized to 48x48 pixels and normalized.

### Data Augmentation
Data augmentation is used to improve the model's performance by generating more training data through random transformations.

### Enhanced Model Definition
An enhanced Convolutional Neural Network (CNN) is defined to classify the facial expressions, with additional layers and regularization techniques.

### Learning Rate Scheduler
A learning rate scheduler is used to adjust the learning rate during training to improve model performance.

### Model Training
The model is trained using the augmented data and the learning rate scheduler.

### Model Evaluation
The model is evaluated on the test set to check its performance. The test accuracy is printed in percentage.

### Training and Validation Loss
The training and validation loss over epochs are visualized.

### Detailed Evaluation
A confusion matrix and classification report are generated to analyze the model's performance in detail.

### Qualitative Results
The model's predictions versus the ground truth are visualized.

## Conclusion
This project successfully builds an enhanced CNN model to classify human facial expressions into seven categories. Future work could involve experimenting with more complex models and exploring additional data augmentation techniques.

## Author
Muhammad Zubair Ahmed Khan (Zubair Khan)