# Leveraging Computer Vision for Automatic Grid Analysis

## Motivation 
Computational imaging techniques using off-the-shelf cameras have been developed to capture electricity grid behavior using illumination from scene lights. These techniques however have a manual pipeline in terms of distinguishing building lights from vehicle lights and street lighting in nighttime urban scenes. In this project, we leverage computer vision techniques for robust localization of relevant building lights in low light scenarios.

## Architecture 
We utilize YOLOv5 as the backbone for training models. Since we want to optimize performance during low-light environment while also minimize latency, YOLOv5 was the ideal choice for object detection with its low inference time and reliable predictions.

## Environment Setup
To clone the repository, run:
```
git clone https://github.com/EPham42747/ersp-2425-vision.git
```
Please note that it is generally _not advised_ to run the project locally, due to the high demand in storage and computing resources. We recommend running the projects on a High-Performance Computing GPU Cluster, such as Google Colab or the Unity Cluster. For our project, our main training environment was the Unity Cluster. 

Install the necessary packages with the command:
```
pip install ultralytics roboflow sklearn cv2 matplotlib
```
After installing all the packages, all the codes should be ready to run!

## Future Work

