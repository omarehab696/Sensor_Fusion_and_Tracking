# Sensor Fusion and Tracking

## Setup Instructions: 

Setting Up the Project Files

First, obtain the project files from [repository](https://github.com/udacity/nd013-c2-fusion-starter.git):

## Installation Instructions for Running Locally

* Cloning the Project

In order to create a local copy of the project, please click on "Code" and then "Download ZIP". Alternatively, you may of-course use GitHub Desktop for this purpose.

* Python

The project has been written using Python 3.7. Please make sure that your local installation is equal or above this version.

* Package Requirements

All dependencies required for the project have been listed in the file `requirements.txt`.
You may either install them one-by-one using pip or you can use the following command to install them all at once: `pip3 install -r requirements.txt`

* Waymo Open Dataset Reader

The Waymo Open Dataset Reader is a very convenient toolbox that allows you to access sequences from the Waymo Open Dataset without the need of installing all of the heavy-weight dependencies that come along with the official toolbox. The installation instructions can be found in `tools/waymo_reader/README.md`.

* Waymo Open Dataset Files

This project makes use of three different sequences to illustrate the concepts of object detection and tracking. These are:

Sequence 1 : 

`training_segment-1005081002024129653_5313_150_5333_150_with_camera_labels.tfrecord`

Sequence 2 : 

`training_segment-10072231702153043603_5725_000_5745_000_with_camera_labels.tfrecord`

Sequence 3 :

`training_segment-10963653239323173269_1924_000_1944_000_with_camera_labels.tfrecord`


To download these files, you will have to register with Waymo Open Dataset first: [Open Dataset – Waymo](https://waymo.com/open/terms) , if you have not already, making sure to note "Udacity" as your institution.


Once you have done so, please click [here](https://console.cloud.google.com/storage/browser/waymo_open_dataset_v_1_2_0_individual_files) to access the Google Cloud Container that holds all the sequences. Once you have been cleared for access by Waymo (which might take up to 48 hours), you can download the individual sequences.


The sequences listed above can be found in the folder "training". Please download them and put the `tfrecord`-files into the `dataset` folder of this project.
