# GarP: Garbage Classification Project

## Overview

GarP is a project aimed at classifying recyclable materials using deep learning techniques. The project utilizes a VGG16-based model to improve recycling effectiveness by accurately identifying different types of garbage.

## Project Structure

- `dataset/`: Contains the dataset used for training and testing the model.
- `model/`: Contains the pretrained VGG16-based model.
- `notebooks/`: Jupyter notebooks for training, evaluation, and real-time testing.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- PyTorch
- torchvision
- OpenCV
- Jupyter Notebook

### Installation

#### Using Anaconda

1. Clone the repository:
    ```bash
    git clone https://github.com/Abdulkadirklc/GarP.git
    cd GarP
    ```

2. Create and activate a virtual environment with Anaconda:
    ```bash
    conda create --name garp_env python=3.7
    conda activate garp_env
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

#### Using Virtual Environment

1. Clone the repository:
    ```bash
    git clone https://github.com/Abdulkadirklc/GarP.git
    cd GarP
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### Training the Model

To train the model, run the `train.ipynb` notebook located in the `notebooks/` directory. This notebook includes data preprocessing, model training, and evaluation steps.

### Image Classification

To classify images using the pretrained model, use the `image_classification.ipynb` notebook. This notebook allows you to load images from the `dataset/` directory and display the classification results.

### Real-Time Classification

For real-time classification using your webcam, run the `realtime_classification.ipynb` notebook. This notebook captures frames from your webcam, processes them using the pretrained model, and displays the predicted class and confidence.

## Data

The dataset and pretrained model are included in the project. You can download them using the link below:

- [Dataset and Pretrained Model](https://drive.google.com/drive/folders/1QfYXCLybIUW2LCI0cdO95LX0aUvrFTTP?usp=sharing)

Place the downloaded files in the respective `dataset/` and `model/` directories.
