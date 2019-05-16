#  #Project 2: Espy
######
&nbsp;
[![Opencv](https://developer.nvidia.com/sites/default/files/akamai/cuda/images/product_logos/OpenCV_Logo_340.jpg)](https://opencv.org/)[![Python](https://www.cupaya.com/wp-content/uploads/2017/09/python-logo.png)](https://www.python.org/)

[![Numpy](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTeXkEA3c2hxTcrZWwVnniXAFiqai51196osD9FWL0_D_Ca7fOT)](https://www.numpy.org/)


## Description
Espy is a python program which uses an open source computer vision and machine learning library, Opencv. The library has more than 2500 optimized algorithms,to detect and recognize faces, identify objects, extract 3D models of objects, produce 3D point clouds from stereo cameras,etc. 

This project includes the principle of object detection using Haar Cascade Classifier. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. These cascade function are stored in xml files. Each Cascade Classifier is used to detect specific features. But for the purpose of face detection, Cascaders such as face, eye and nose were used in this project. The cascaders process real time video recording and create boxes around the faces to differentiate the faces, noses and eyes.

For more information on how Face Haar Cascaders work - [Face Detection Using Haar Cascades]


### Technology
These are the follwing libraries which was made use of in this project:

* [Numpy] - NumPy is a library for the Python programming language which provides    additional support for processing large, multi-dimensional arrays and matrices.
* [Python] - An easy to pick up proramming language and fun to play with. 
* [Opencv] - OpenCV (Open Source Computer Vision Library) is an open source computer vision and machine learning software library.


## Setup

##### This was build on Windows 8.1.

These were the pre-requisities :

##### Install [Numpy] using pip
```sh
$ pip install Numpy
```
##### Install [Opencv] using pip
```sh
$ pip install opencv-python
$ pip install opencv-contrib-python
```
##### Stratify requires [Python](https://www.python.org/) 3.6+ to run.

Click the python thumbnail to go to Python Download Page 
[![Click to go to Python Download Page](https://www.cupaya.com/wp-content/uploads/2017/09/python-logo.png)](https://www.python.org/downloads/)

# Download
```sh
$ git clone https://github.com/Alpha-github/face_detection.git
```


## Important:
 ##### The detection of images may take some time and are also not very accurate.The detection of, especially the eyes and nose, gets better with adequate lighting and when the object being recorded is still.
#
## License
#### Public


   [Opencv]: <https://opencv.org/>
   [Python]: <https://www.python.org/>
   [Numpy]: <https://www.numpy.org/>
   [Click to go to Python Download Page]: <https://www.python.org/downloads/>
   [Face Detection Using Haar Cascades]:<https://docs.opencv.org/3.4.1/d7/d8b/tutorial_py_face_detection.html>
   
  