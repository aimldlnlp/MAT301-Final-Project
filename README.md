# Implementation of YOLOv8 in Waste Classification (Case Study: KRTMI Robot ASTRO_24)

## Introduction
This project focuses on developing a Waste Classification Robot that utilizes the YOLOv8 model for the automatic sorting of waste materials. By collecting a dataset of 10,320 images across 9 waste categories (e.g., plastic bottles, wet leaves, and paper), we trained the model to accurately identify and classify common waste types. The data collection process involved gathering waste from various sources, capturing high-quality images, and performing careful data labeling.

## Data Acquisition
- **Dataset Size:** 10,320 images
- **Categories:** 9 categories including plastic, paper, and metal.
- **Method:** Collected from households and public spaces, ensuring diverse representation.

## Data Preprocessing
Images were resized to 640x640 pixels and underwent various augmentation techniques (e.g., rotation, flipping) to enhance model robustness. The dataset was split into training, validation, and testing sets for effective training.

## Model Development
We implemented YOLOv8 for object detection using Google Colaboratory, adjusting hyperparameters for optimal performance.

## Note on Code Availability
Please note that the code for this project cannot be shared due to privacy and confidentiality issues. However, the methodology and results are presented here to demonstrate the project's impact and effectiveness.
