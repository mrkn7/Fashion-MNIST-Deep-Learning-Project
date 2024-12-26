# Fashion-MNIST-Deep-Learning-Project

This repository contains a deep learning project based on the Fashion-MNIST dataset. The goal is to classify images of clothing articles into one of 10 categories using a fully connected neural network implemented in PyTorch.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Setup Instructions](#setup-instructions)
4. [Usage](#usage)
5. [Results](#results)
6. [License](#license)

## Introduction
The Fashion-MNIST dataset is a collection of grayscale images of size 28x28 pixels, each belonging to one of 10 categories:
- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

This project implements a deep learning model to classify these images accurately. The dataset is split into training and testing sets with 60,000 and 10,000 samples, respectively.

## Project Structure
```
Fashion-MNIST-DeepLearning/
|
├── images/                     # Images used in the project
├── notebooks/                  # Jupyter Notebook files
│   ├── part_i.ipynb            # Preprocessing and initial modeling
│   ├── part_ii.ipynb           # Hyperparameter tuning and results
├── README.md                   # Project documentation
├── requirements.txt            # Python dependencies
├── .gitignore                  # Ignored files and folders
├── LICENSE                     # License file
```

## Setup Instructions
1. Clone the repository:
    ```bash
    git clone https://github.com/mrkn7/Fashion-MNIST-DeepLearning.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Fashion-MNIST-DeepLearning
    ```
3. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows: venv\Scripts\activate
    ```
4. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

### 1. Preprocessing and Model Training
Run the preprocessing and training code using the Jupyter notebooks:
```bash
jupyter notebook notebooks/part_i.ipynb
```

### 2. Hyperparameter Tuning
Optimize the model by running the second notebook:
```bash
jupyter notebook notebooks/part_ii.ipynb
```

### 3. Modular Code
Alternatively, use the Python scripts for preprocessing, model training, and evaluation:
- Data Preprocessing:
  ```bash
  python src/data_preprocessing.py
  ```
- Model Training:
  ```bash
  python src/model.py
  ```
- Evaluation:
  ```bash
  python src/evaluate.py
  ```

## Results
The trained model achieves an accuracy of approximately 90% on the Fashion-MNIST test dataset. For detailed results, see the the evaluation notebook (`part_ii.ipynb`).

## License
This project is licensed under the MIT License. See the `LICENSE` file for more information.

