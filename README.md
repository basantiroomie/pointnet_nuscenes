# PointNet-based 3D Object Detection on nuScenes Dataset

## Overview

Implemented and experimented with PointNet architecture for 3D point cloud processing and object detection using the large-scale autonomous driving nuScenes dataset. The project involves processing multi-sensor data (LiDAR, cameras, radar) to detect and classify objects in 3D space, leveraging deep learning on raw point cloud data.
This repository appears to focus on using PointNet, a deep learning architecture for point cloud processing, with the nuScenes dataset, which is a large-scale autonomous driving dataset. It involves 3D point cloud data processing and analysis using PointNet.

## Getting Started

To use or explore the project:

1. Clone the repository:
   ```bash
   git clone https://github.com/basantiroomie/pointnet_nuscenes.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pointnet_nuscenes
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook testmini.ipynb
   ```
4. Follow the code and comments in the notebook to understand the implementation and usage.

## Requirements

- Python (version compatible with Jupyter Notebook)
- Jupyter Notebook
- Dependencies for PointNet and nuScenes dataset processing tensorflow


## Tech Stack and Tools:

- **Deep Learning Framework:** PyTorch or TensorFlow (common for PointNet implementations)  
- **Point Cloud Processing:** PointNet architecture — a neural network designed to directly consume unordered 3D point sets, robust to input perturbations and efficient for classification and segmentation tasks
- **Dataset:** nuScenes — a comprehensive autonomous driving dataset with synchronized data from 6 cameras, 1 LiDAR, 5 RADAR sensors, GPS, 
- **Data Handling:** nuScenes devkit and Python SDK for loading, preprocessing, and augmenting multi-sweep LiDAR point clouds and sensor fusion 
- **3D Object Detection Pipeline:**  
  - Point cloud segmentation and feature extraction with PointNet/PointNet++  
  - 3D bounding box estimation  
  - Fusion of temporal LiDAR sweeps and multi-modal sensor data (RGB, radar) to enhance detection accuracy
- **Development Environment:** Jupyter Notebook for prototyping and visualization  
- **Additional Techniques:** Data augmentation (random rotations, jitter), coordinate normalization (T-Net), and potentially transformer-based feature learning for improved robustness

## Key Contributions:
- Applied PointNet to real-world autonomous driving data for 3D object detection  
- Utilized multi-sensor fusion and temporal point cloud aggregation to improve detection performance  
- Demonstrated understanding of deep learning on irregular 3D data and autonomous vehicle perception pipelines
