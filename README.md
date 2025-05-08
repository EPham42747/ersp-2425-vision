# Leveraging Computer Vision for Automatic Grid Analysis

## Motivation 
Computational imaging techniques using off-the-shelf cameras have been developed to capture electricity grid behavior using illumination from scene lights. These techniques however have a manual pipeline in terms of distinguishing building lights from vehicle lights and street lighting in nighttime urban scenes. In this project, we leverage computer vision techniques for robust localization of relevant building lights in low light scenarios.

## Architecture 
We utilize YOLOv5 as the backbone for training models. Since we want to optimize performance during low-light environment while also minimize latency, YOLOv5 was the ideal choice for object detection with its low inference time and reliable predictions.

## Methodology


## Results

## Future Work
