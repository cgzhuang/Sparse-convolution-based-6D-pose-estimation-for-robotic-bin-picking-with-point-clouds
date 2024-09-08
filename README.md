# Sparse Convolution Based 6D Pose Estimation for Robotic Bin-Picking with Point Clouds

## Overview

This repository contains the code and documentation for our research on sparse convolution-based 6D pose estimation for robotic bin-picking using point clouds. Our method significantly enhances the accuracy and efficiency of pose estimation in scenarios involving stacked objects.

## Key Contributions

1. **Two-Stage Deep Learning Framework:** A comprehensive framework based on sparse convolution and point clouds is proposed, significantly improving pose estimation accuracy and efficiency. The first stage involves instance segmentation and initial pose estimation, while the second stage focuses on pose refinement.
   
2. **Efficient Dataset Generation and Labeling Method:** Utilizing OpenGL for real-time rendering and PhysX for realistic physical simulations, we developed a method that enables rapid creation of large-scale, high-quality synthetic datasets. This method supports the generation of diverse and complex data tailored to various industrial objects and bin-picking scenarios.
   
3. **Pose Refinement Network:** A dedicated network is introduced to accurately predict transformations between point clouds based on initial poses. This network extracts detailed spatial features using a 3D U-Net architecture and employs an attention mechanism to highlight critical features, resulting in highly accurate pose adjustments.

## Video Demonstration

A video demonstrating our work can be found at the link below:

https://drive.google.com/file/d/1IwzTgrB2asHrE-xx8DkGoxQhN9yXViGM/view?usp=sharing

## Data Generate Tool

https://drive.google.com/file/d/1dQaR7mqd__zJdzbeiev0W39tysSjv3-u/view?usp=sharing

If you need the network structure or more detailed code, please feel free to contact us at nwh1093412390@sjtu.edu.cn

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


