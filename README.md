# Preprocessing and YOLO Inference for Cell Detection and Classification in Neubauer Chamber Microscopy Images

## Overview

This repository contains a complete pipeline for preprocessing microscopy images acquired from a Neubauer chamber and utilizing the YOLO (You Only Look Once) object detection algorithm for the detection and classification of cells. The primary goal of this project is to automate the preprocessing of these images and employ YOLO to accurately identify and classify different types of cells.

## Repository Structure

- `Notebooks/`: Jupyter notebooks demonstrating the preprocessing and YOLO inference steps.
- `Demo Microscopy Data/`: Examples on: Microscopy images, preprocessed cropped image with Neubauer grid size and detection output.
- `README.md`: Project description and setup instructions.

## Features and Functionalities

### File Management
- Navigating to specific directories and subdirectories based on creation time.
- Listing and counting files in a directory.
- Loading images and other data files from folders.

### Image Processing
- Converting TIFF images to stacks.
- Implementing a sliding window technique for image cropping.
- Loading images into a collection.

### Data Extraction and Processing
- Reading and parsing text files to extract relevant data.
- Extracting bounding box data from text files.
- Sampling data for analysis.

### Data Analysis
- Calculating statistical measures such as averages and standard deviations for live and dead cell count.
- Aggregating data for analysis.

### Data Visualization
- Plotting data.
- Creating comparative plots for different data sets.




### Prerequisites

- Python 3.7 or higher
- YOLOv5 repository
