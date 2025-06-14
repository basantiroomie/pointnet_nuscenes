# PointNet-based 3D Object Detection on nuScenes Dataset

**Description:**  
Implemented and experimented with PointNet architecture for 3D point cloud processing and object detection using the large-scale autonomous driving nuScenes dataset. The project involves processing multi-sensor data (LiDAR, cameras, radar) to detect and classify objects in 3D space, leveraging deep learning on raw point cloud data.

**Tech Stack and Tools:**

- **Deep Learning Framework:** PyTorch or TensorFlow (common for PointNet implementations)  
- **Point Cloud Processing:** PointNet architecture — a neural network designed to directly consume unordered 3D point sets, robust to input perturbations and efficient for classification and segmentation tasks[7][8]  
- **Dataset:** nuScenes — a comprehensive autonomous driving dataset with synchronized data from 6 cameras, 1 LiDAR, 5 RADAR sensors, GPS, and IMU[1][3]  
- **Data Handling:** nuScenes devkit and Python SDK for loading, preprocessing, and augmenting multi-sweep LiDAR point clouds and sensor fusion[3][5]  
- **3D Object Detection Pipeline:**  
  - Point cloud segmentation and feature extraction with PointNet/PointNet++  
  - 3D bounding box estimation  
  - Fusion of temporal LiDAR sweeps and multi-modal sensor data (RGB, radar) to enhance detection accuracy[4][6]  
- **Development Environment:** Jupyter Notebook for prototyping and visualization  
- **Additional Techniques:** Data augmentation (random rotations, jitter), coordinate normalization (T-Net), and potentially transformer-based feature learning for improved robustness[4][7]

**Key Contributions:**  
- Applied PointNet to real-world autonomous driving data for 3D object detection  
- Utilized multi-sensor fusion and temporal point cloud aggregation to improve detection performance  
- Demonstrated understanding of deep learning on irregular 3D data and autonomous vehicle perception pipelines[6][7]

