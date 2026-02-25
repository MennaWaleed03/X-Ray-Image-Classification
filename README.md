# X-Ray Image Classification Notebook – Deep Learning Diagnostic System

## Overview
This notebook implements a **medical X-Ray image classification system** using **PyTorch**.  
It explores multiple neural network architectures, including custom **CNNs**, **VGG**, and **ResNet**, to classify X-Ray images accurately.  
The **ResNet implementation is flexible**, allowing dynamic specification of the number of layers (e.g., ResNet-18, ResNet-34, ResNet-50) when initializing the model.

---

## Features
- **Custom CNN Architectures:** Implemented VGG and ResNet from scratch for full control.  
- **Flexible ResNet:** Specify any ResNet depth dynamically by passing a value to the class.  
- **Image Preprocessing:** Preprocess X-Ray images using **OpenCV**.  
- **Model Comparison:** Evaluated multiple architectures (MNN, CNN, VGG, ResNet) and compared performance metrics; ResNet achieved the best results.  
- **End-to-End Notebook:** Includes preprocessing, model training, evaluation, and visualization of results.

---

## Technologies Used
- **Python**  
- **PyTorch** for deep learning  
- **OpenCV** for image preprocessing  
- **CNN, VGG, ResNet (flexible depth)**  
- **Evaluation Metrics:** Accuracy, loss curves, classification reports

---

## Usage
1. Open the notebook in **Jupyter Notebook** or **JupyterLab**.  
2. Preprocess your X-Ray dataset as described in the first cells.  
3. Train the models and experiment with different architectures.  
4. For flexible ResNet:




5. Evaluate results and visualize performance metrics.

Results

ResNet outperformed other architectures in classification accuracy.

