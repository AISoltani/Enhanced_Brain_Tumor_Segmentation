# Enhanced_Brain_Tumor_Segmentation
Lightweight U-Net for Brain Tumor Detection


This repository contains the implementation of a simplified U-Net model for detecting brain tumors. The model has been optimized to reduce complexity and improve usability in resource-constrained environments.

Key Features
Reduced Model Complexity: Minimized convolutional layers in the U-Net architecture.
Optimized Image Size: Operates on 128x128 images to reduce computational load.
Kaggle Dataset Integration: Easily download datasets from Kaggle using the API key.
Getting Started
Prerequisites
Python (>=3.7)
Kaggle account with an API key
Google Colab (optional, but recommended for seamless integration)
Installation
Clone the repository and ensure you have the required dependencies installed:

```bash
git clone https://github.com/your_username/brain-tumor-detection.git
cd brain-tumor-detection
pip install -r requirements.txt
```

Dataset Preparation
Obtain Kaggle API Key:
Log into your Kaggle account and download your API key (kaggle.json).

Upload API Key to Colab:
Upload your kaggle.json file when prompted in the notebook.

Download Dataset:
Run the provided code to automatically fetch and store the dataset in the designated directory.

Running the Notebook
Open the notebook in your preferred environment:

Google Colab: Upload the notebook and run each cell sequentially.
Local Setup: Ensure all dependencies are installed, and execute the notebook using Jupyter or any compatible tool.
Model Overview
The model is a lightweight U-Net with reduced layers and operates on downscaled image data (128x128). This allows for faster training and inference without significant loss in accuracy.

Results
Performance: Achieves high accuracy with minimal computational cost.
Efficiency: Suitable for real-time applications on less powerful devices.
Repository Structure
notebooks/ - Contains the main Jupyter notebook.
data/ - Folder for storing datasets (not included in the repository).
models/ - Contains the trained model weights (optional).
