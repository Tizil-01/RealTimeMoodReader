# RealTimeMoodReader
## Project Overview

This project implements a real-time emotion detection system using various machine learning techniques like random forest, gradient boosting, convolutional neural networks (CNNs) on facial expressions. The system is trained on a dataset of facial images labeled with seven emotions: angry, disgust, fear, happy, neutral, sad, surprise. The trained model is then used for real-time inference to detect emotions from live webcam feeds.

## Project Structure

### Files

- **code.py**: Python script for training the CNN model, evaluating its performance, and exploring various machine learning algorithms for emotion detection.
- **realtime.py**: Python script for real-time emotion detection using the trained CNN model and a webcam.
- **requirements.txt**: List of dependencies required to run the project.
- **report.pdf**: Report containing detailed analysis, results, and findings from the experiments conducted.

### code.py

This script handles:
- Data preprocessing: Loading images, labeling, and preparing them for training.
- Model training: CNN architecture using Keras with TensorFlow backend.
- Model evaluation: Calculating accuracy, precision, recall, and generating confusion matrix.
- Experimentation with other machine learning algorithms like AdaBoost, Random Forest, etc.
- Visualization: Plotting accuracy trends across epochs and displaying sample images with predictions.

### realtime.py

This script includes:
- Real-time emotion detection using OpenCV for webcam access.
- Haar Cascade classifier for face detection.
- Preprocessing of detected faces for input into the trained CNN model.
- Display of detected emotions in real-time on the webcam feed.

### requirements.txt

Contains Python packages required to run the project. Install dependencies using:

```bash
pip install -r requirements.txt
