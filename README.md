# Breast Cancer Prediction Model

This repository contains a **Jupyter Notebook** that implements a deep learning model using **PyTorch** to predict breast cancer based on the **Sklearn Breast Cancer dataset**. The model is built using a multi-layer architecture and is trained to classify cancer as **malignant** or **benign**, achieving an impressive **97.37% test accuracy** after 100 epochs.

## Key Features

- **Deep Learning Architecture**: A multi-layer neural network model utilizing ReLU activation functions and the Adam optimizer for efficient gradient descent.
- **High Performance**: Achieved a **97.37% test accuracy** and **97.36% training accuracy** after 100 epochs with a **loss of 0.1210**.
- **Data Preprocessing**: Used **train_test_split** to split the data and **StandardScaler** for feature scaling to improve the model's performance.
- **GPU Acceleration**: Enabled **CUDA** for GPU acceleration to speed up model training.
- **Evaluation**: Evaluated the model's performance using **no_grad** to optimize inference and avoid unnecessary gradient computations.

## Tools & Technologies

- **Python**  
- **PyTorch**: For creating and training the deep learning model.  
- **Scikit-Learn**: For loading the dataset, data splitting, and scaling.  
- **CUDA**: For GPU acceleration to optimize training time.  
- **Adam Optimizer**: Used for gradient descent optimization.  
- **Tensor Operations**: For efficient matrix and tensor operations during training and evaluation.

## Setup

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/AlekhyaGudibandla/Breast-Cancer-Prediction-Model.git
    ```

2. **Install Dependencies**:
    Install the necessary Python libraries using:
    ```bash
    pip install -r requirements.txt
    ```
    Ensure you have **PyTorch** and **Scikit-Learn** installed.

3. **Open the Notebook**:
    Navigate to the directory and open the **Jupyter notebook** file:
    ```bash
    jupyter notebook Breast_Cancer_Prediction.ipynb
    ```

4. **Run the Notebook**:
    Execute the cells in the notebook to train the model and evaluate its performance.

## Model Overview

- **Dataset**: Sklearn's Breast Cancer dataset.
- **Model Architecture**: A multi-layer feedforward neural network with ReLU activation.
- **Output**: Predicts whether the tumor is **Malignant** or **Benign**.
- **Performance Metrics**: Accuracy and loss values are displayed at the end of the training.

## Results

- **Test Accuracy**: **97.37%**
- **Training Accuracy**: **97.36%**
- **Loss after 100 Epochs**: **0.1210**

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Any improvements to the model, evaluation metrics, or documentation are welcome!

---
