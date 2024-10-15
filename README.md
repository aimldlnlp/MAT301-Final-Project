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
We implemented YOLOv8 for object detection using Google Colaboratory, adjusting hyperparameters for optimal performance. The model was trained for 100 epochs, achieving a high mean average precision (mAP) of 99.4% with 100% precision.

## Results
The YOLOv8 model demonstrated excellent performance, achieving:
- **Precision:** 100%
- **Recall:** 99.6%
- **mAP:** 99.4%

## Conclusion
The project successfully illustrates the capability of computer vision, particularly YOLOv8, in accurately identifying and classifying waste. This technology has significant potential to enhance waste management systems, contributing to environmental sustainability.

## License
This project is licensed under the MIT License.

## Acknowledgments
Thanks to the KRTMI ASTRO_24 team for their collaboration and support in this endeavor.

