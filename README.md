# Breast Cancer Prediction Model

This repository contains a deep learning model developed using **PyTorch** to predict breast cancer based on the well-known **Sklearn Breast Cancer dataset**. The model uses a multi-layer architecture to classify cancer as malignant or benign, with a high test accuracy of **97.37%** after 100 epochs.

## Key Features

- **Deep Learning Architecture**: A multi-layer neural network with ReLU activation functions and Adam optimizer for efficient gradient descent.
- **Model Performance**: Achieved a test accuracy of **97.37%** and a training accuracy of **97.36%** after 100 epochs with a loss of **0.1210**.
- **Data Processing**: Utilized `train_test_split` for dataset splitting, and applied **StandardScaler** for feature scaling to improve model performance.
- **GPU Acceleration**: Leveraged CUDA for GPU acceleration, significantly reducing training time and enhancing computational efficiency.
- **Evaluation**: The model's performance was evaluated using `no_grad` to prevent gradient computation during evaluation, ensuring efficient inference.

## Tools & Technologies

- **Python**  
- **PyTorch**: For implementing the neural network model.  
- **Scikit-Learn**: For dataset loading, data preprocessing, and splitting.  
- **CUDA**: For GPU acceleration during model training.  
- **Adam Optimizer**: For efficient gradient descent during training.  
- **Tensor Operations**: To perform computations on tensors for training and evaluation.

## Setup

To get started with the Breast Cancer Prediction Model, follow the steps below:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/AlekhyaGudibandla/Breast-Cancer-Prediction-Model.git
    ```

2. **Install Dependencies**:
    Install the necessary Python packages using:
    ```bash
    pip install -r requirements.txt
    ```
    You may need to install PyTorch and Scikit-Learn if they are not already installed.

3. **Run the Model**:
    After setting up, run the model training using the script:
    ```bash
    python train_model.py
    ```

4. **GPU Acceleration (Optional)**:
    If you have a compatible NVIDIA GPU, ensure CUDA is installed for hardware acceleration or feel free to use Google colab for better perfomance.

## Model Details

- **Input**: Features from the Sklearn Breast Cancer dataset.
- **Output**: Predicted labels: **Malignant** or **Benign**.
- **Evaluation**: The model's performance is evaluated on the test set with metrics like accuracy and loss.

## Results

- **Test Accuracy**: **97.37%**
- **Training Accuracy**: **97.36%**
- **Loss after 100 Epochs**: **0.1210**

## Contributing

Feel free to contribute to this project by submitting issues, pull requests, or suggestions. Whether it's improving model performance, adding more evaluation metrics, or enhancing documentation, your contributions are welcome!

---
