# Pneumonia Detection from Chest X-rays

This project uses **Deep Learning (MobileNetV2)** to detect **Pneumonia** from chest X-ray images.  
Implemented in **Python** using **TensorFlow/Keras**, it can be run in **Google Colab**.

## Project Structure
pneumonia-detection/
├── pneumonia_detection.ipynb # Colab notebook with training & testing
├── pneumonia_model.h5 # Trained model file
├── README.md # Project description

---

## Features

- Detects **Normal vs Pneumonia** in chest X-rays.
- Uses **Transfer Learning** (MobileNetV2) for improved accuracy.
- Can test **any uploaded X-ray image**.
- Saves the trained model for future use.

## Requirements

- Python 3.x  
- TensorFlow  
- NumPy  
- Matplotlib  
- Pillow  
- scikit-learn  

Install packages with:

```bash
pip install tensorflow numpy matplotlib pillow scikit-learn

## How to Run
1.Open pneumonia_detection.ipynb in Google Colab.
2.Upload the dataset (Chest X-ray Pneumonia Dataset) or use test images.
3.Train the model (optional, or use the pre-trained pneumonia_model.h5).
4.Test on X-ray images to get predictions.

## Dataset
Chest X-ray Pneumonia Dataset on Kaggle

## Author
Dhanashree Kulkarni
dhanukulkarni2004@gmail.com


