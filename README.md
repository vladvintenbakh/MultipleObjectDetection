# Object Detection with SSD Mobilenet - Multiple Objects

## Project Objective
The goal of this project is to use a pre-trained SSD Mobilenet model to perform object detection on custom images, focusing on identifying two objects. The project demonstrates the steps involved in data preprocessing, model setup, and inference using TensorFlow in Google Colab with GPU acceleration.

### Methods Used
* Object Detection
* Data Preprocessing
* Model Training & Inference
* Evaluation Metrics

### Technologies
* Python
* Jupyter/Google Colab
* Pandas
* NumPy
* Matplotlib
* TensorFlow

## Project Description
This project implements an object detection model using the SSD Mobilenet architecture. The goal is to detect multiple objects within custom images, with a focus on identifying two objects per image. The notebook demonstrates the complete pipeline from setting up the environment, preprocessing the dataset, and running inference on the images.

Key areas of focus include:
1. Setting up the environment in Google Colab, including mounting Google Drive for data access.
2. Data preprocessing, including image resizing and augmentation.
3. Loading a pre-trained SSD Mobilenet model.
4. Running inference and visualizing the results with bounding boxes.
5. Evaluating model performance and discussing the challenges, particularly regarding the confidence level in detecting the second object.

As noted, the model's performance on detecting the second object is suboptimal due to low confidence scores, and further tuning is required to improve this aspect.

## Project Needs
- Data preparation and preprocessing
- Model fine-tuning for better object detection
- Improved confidence scores for detecting secondary objects
- Inference optimization and visualization

## Getting Started

1. Clone this repo (for help, see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Open the Jupyter notebook in Google Colab, ensuring GPU is enabled for TensorFlow.
3. Follow the notebook instructions to set up the environment and run the inference.

## Featured Notebooks
* [4_Multiple_Objects_Detection_Full.ipynb](https://github.com/vladvintenbakh/MultipleObjectDetection/blob/main/4_Multiple_Objects_Detection_Full.ipynb)
