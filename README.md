# Preprocessing and YOLO Inference for Cell Detection and Classification in Neubauer Chamber Microscopy Images

## Overview

This repository contains a complete pipeline for preprocessing microscopy images acquired from a Neubauer chamber and utilizing the YOLO (You Only Look Once) object detection algorithm for the detection and classification of cells. The primary goal of this project is to automate the preprocessing of these images and employ YOLO to accurately identify and classify different types of cells.

## Repository Structure

- `notebooks/`: Jupyter notebooks demonstrating the preprocessing and YOLO inference steps.
- `src/`: Source code for preprocessing and YOLO inference.
- `data/`: Example microscopy images and preprocessed images.
- `models/`: Pre-trained YOLO models and training scripts.
- `results/`: Sample output images and detection results.
- `requirements.txt`: Required Python packages for the project.
- `README.md`: Project description and setup instructions.

## Features

- **Image Preprocessing**:
  - **Noise Reduction**: Apply filters such as Gaussian and Median to remove noise and enhance image clarity.
  - **Contrast Enhancement**: Improve cell visibility using techniques like histogram equalization and adaptive contrast enhancement.
  - **Segmentation**: Isolate regions of interest (ROI) to focus on areas containing cells.

- **YOLO Inference**:
  - **Detection**: Utilize the YOLO algorithm to detect cells within the preprocessed images.
  - **Classification**: Classify detected cells into different categories based on their morphological characteristics.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- Install required packages:
  ```bash
  pip install -r requirements.txt
