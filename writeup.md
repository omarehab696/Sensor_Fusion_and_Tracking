# Sensor Fusion and Tracking Workflow

## The Goal of this Project

the goal of this project is to fuse measurements from LiDAR and camera and track vehicles over time. You will be using real-world data from the Waymo Open Dataset, detect objects in 3D point clouds and apply an extended Kalman filter for sensor fusion and tracking.

## The Soliving Sequance of this Project
* Visualize range image channels
 
Please locate two images from separate data sets within the Images folder that have been stacked together to display range and intensity information.

* Visualze point-cloud
 
Please locate examples within the Images folder that display vehicles along with their features.

* BEV-map coordinates

* Compute intensity layer of bev-map

The settings have been modified to make the vehicles visible.

* Compute height layer of bev-map

* Add Second Model

The fpn_resnet model has been implemented, and additional hyperparameters have been included, as specified in the test.py file.

* Bounding boxes

Bounding boxes have been included, but it should be noted that the x and y coordinates need to be flipped to comply with the requirements of the Bird's Eye View (BEV) format.

* IOU calculate & count true positive
* Count false negative and false positive
* compute percision and recall

## Observation


In this project, I applied the knowledge acquired from the lessons to extract lidar data from the Waymo dataset and generate images for the necessary channels. These images were later used in conjunction with a machine learning model to detect the surrounding environment.

Finally, I evaluated the model myself based on the data and results obtained.
