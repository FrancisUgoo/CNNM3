# Facial Expression Classification Deep Learning Model

Welcome to the **Facial Expression Classification** project! This open-source project aims to build a deep learning model capable of identifying and classifying three distinct facial expressions in real-time:

- **Showing Interest**
- **Lack of Interest**
- **Neutral**

The project utilizes **Python**, **Keras**, and **TensorFlow** to develop, train, and deploy the model for real-time facial expression recognition.

## Project Overview

This project focuses on training deep learning models to identify and classify three specific facial expressions: "Showing Interest," "Lack of Interest," and "Neutral." The model was developed with experimentation in mind and serves as a foundation for further research and improvements. Several approaches and architectures were tested during the research phase to assess the effectiveness of different techniques in achieving accurate classifications.

Although the project is still in the experimental phase and is not yet fully optimized, it is open-source, and contributions are highly encouraged. You are welcome to modify, enhance, or extend the project to suit your needs and contribute to its future growth.

## Project Structure

This repository includes the following key components:

### 1. **test.zip**
Contains the zipped test dataset of images used for evaluating the model's performance.

### 2. **training.zip**
Contains the zipped training dataset of images used for training the model.

### 3. **models folder**
This folder contains the models that were created and tested during the research phase. These models represent various approaches to facial expression classification.

### 4. **preferred_CNNM3_model.7z**
The final, optimized model that was selected after experimentation. This model has been fine-tuned for identifying the three facial expressions: "Showing Interest," "Lack of Interest," and "Neutral."

### 5. **haarcascades folder**
Contains several pre-trained Haar Cascade XML files for face detection, which is a crucial first step in facial expression classification.

### 6. **haarcascade_frontalface_default.xml**
This specific Haar Cascade file was selected and used for detecting frontal faces in the input images.

### 7. **proj1.ipynb**
The main Jupyter notebook where the project was developed. It includes the full process of model training, evaluation, and saving. The notebook serves as a step-by-step guide for building and fine-tuning the model.

### 8. **snap.ipynb**
A Jupyter notebook used for testing the real-time face capture and expression prediction process. This notebook allows you to use your webcam to detect and classify facial expressions in real time.

### 9. **epochs_to_show_accuracy folder**
Contains `.txt` files documenting the prediction results and performance metrics at various phases of the research. These files help track the progress and performance of the models during training and evaluation.

## Purpose of the Project

The primary objective of this project is to develop a deep learning model capable of classifying three distinct facial expressions: "Showing Interest," "Lack of Interest," and "Neutral." This system can be integrated into various applications such as interactive AI systems, marketing, or user engagement tools where detecting interest levels is crucial.

The project uses **Python**, **Keras**, and **TensorFlow** to implement the model. Although it is still in the experimental stage, the model demonstrates the feasibility of real-time facial expression recognition and serves as a foundation for further refinement and application development.

## Getting Started

### Prerequisites

To run this project locally, you will need to install the following dependencies:

- Python 3.x
- Keras
- TensorFlow
- OpenCV
- Matplotlib

You can install the required libraries by running:

```bash
pip install -r requirements.txt
```

### Usage

1. **Prepare the Data:**
   - Unzip the `training.zip` and `test.zip` files into their respective directories to prepare the training and test datasets.

2. **Train the Model:**
   - Open the `proj1.ipynb` notebook to start the model training process. It covers data preprocessing, model building, and training, along with performance evaluation.

3. **Real-Time Prediction:**
   - Use the `snap.ipynb` notebook to test the real-time capture and prediction functionality. This notebook interacts with your webcam to detect facial expressions and classify them as "Showing Interest," "Lack of Interest," or "Neutral."

4. **Evaluate Model Performance:**
   - You can track the model's performance through the `epochs_to_show_accuracy` folder, which contains `.txt` files documenting accuracy and other metrics during various stages of the research.

5. **Using the Final Model:**
   - The `preferred_CNNM3_model.7z` contains the final, optimized model, which can be tested directly for real-time facial expression recognition.

## Contributing

This project is still in the experimental phase, and improvements are always welcome! If you have ideas for enhancing the model, code, or documentation, please feel free to fork the repository, make changes, and submit a pull request.

Potential areas for improvement:
- Experiment with different neural network architectures (e.g., CNN, LSTM, etc.).
- Implement data augmentation to improve model robustness.
- Fine-tune the model on new datasets for better generalization and accuracy.
- Optimize real-time prediction speed and model efficiency.

## License

This project is open-source and licensed under the MIT License. You are free to use, modify, and distribute the code as per the terms of the license.

## Acknowledgments

This project utilizes several open-source tools and libraries, including:
- **TensorFlow** and **Keras** for building and training deep learning models.
- **OpenCV** for face detection and image processing.
- **Matplotlib** for visualizing results and performance metrics.

---

We encourage you to explore, experiment, and contribute to this project. Together, we can enhance the model and create a more accurate and efficient system for real-time facial expression recognition!
