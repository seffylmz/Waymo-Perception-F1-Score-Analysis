# Waymo-Perception-F1-Score-Analysis

This project aims to measure the F1 score of the Waymo perception system by detecting surrounding vehicles using LiDAR and camera data from the Waymo Open Dataset. The detection results will be compared with the ground-truth labels provided in the dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Evaluation](#evaluation)
- [Results](#results)
- [TODO](#todo)

## Introduction

The goal of this project is to evaluate the performance of the Waymo perception system by calculating the F1 score for vehicle detection. The project leverages LiDAR and camera data from the Waymo Open Dataset to detect vehicles, and these detections are then compared against the ground-truth annotations to compute precision, recall, and the F1 score.

## Dataset

The project utilizes the [Waymo Open Dataset](https://waymo.com/open/), a large-scale autonomous driving dataset with annotated LiDAR and camera data.

### Ground-Truth Labels

The dataset includes ground-truth labels for various objects, including vehicles, pedestrians, cyclists, and more. These labels will be used as a benchmark to evaluate the accuracy of the vehicle detection.

## Installation

### Prerequisites

Coming soon.

### Setup

Coming soon.

### Evaluating the F1 Score

Coming soon.

## Methodology

1. **Preprocessing:** The LiDAR and camera data are preprocessed.
2. **Detection:** A detection algorithm is applied to identify vehicles in the environment.
3. **Comparison:** The detected vehicles are compared with the ground-truth labels to compute precision, recall, and F1 score.

## Evaluation

The performance of the detection system is evaluated using the following metrics:

- **Precision:** Measures the accuracy of the detected vehicles.
- **Recall:** Measures the completeness of the detection.
- **F1 Score:** The harmonic mean of precision and recall, providing a balanced measure of the system's performance.

## Results

The F1 score for vehicle detection will be reported here after running the evaluation. Sample results and visualizations of the detection will also be included.

## TODO

Below is a list of tasks that need to be completed for this project:

- [ ] **Data Preparation:**
  - [ ] Preprocess LiDAR data.
  - [ ] Synchronize camera data with LiDAR timestamps.
  
- [ ] **Algorithm Development:**
  - [ ] Implement vehicle detection algorithm.
  - [ ] Integrate camera data for multi-sensor fusion.
  - [ ] Optimize detection algorithm for real-time performance.

- [ ] **Evaluation:**
  - [ ] Develop a script to compare detection results with ground-truth labels.
  - [ ] Compute and log precision, recall, and F1 scores.
  - [ ] Create visualizations for detected vs. ground-truth comparisons.


