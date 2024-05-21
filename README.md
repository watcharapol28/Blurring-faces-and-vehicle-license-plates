# Blurring-faces-and-vehicle-license-plates
Topic : Preventing personal data breaches through image processing and machine learning.
</br>
Knowledge : Image processing, Computer vision, Machine learning</br>
Tools : Python, OpenCV, YOLOv8</br></br>


## About project
This project aims to propose guidelines for preventing personal data breaches and complying with personal data laws in the field of images or video especially and also intends to study machine learning and image processing.</br>
- Collect data from Youtube videos and collect data manually.</br>
- Using Roboflow for label, preprocessing and Augmentations.</br>
- Using yolov8m and faster-RCNN to train model.</br>
- Using openCV to read data from image or video for bluring face and vehicle license plate.</br> </br> 

<a> (-) Model detected on face and vehicle license plate</a></br>
<img src = "Other/Detected_GIF.gif" />
</br>
<a> (-) Blurred where detected</a></br>
<img src = "Other/Blurred_GIF.gif" />
</br>


## Installation
To use the Blurring faces and vehicle license plate, follow these step :</br></br>
<a href = "https://www.python.org/downloads/">Install python</a> <a>from version 3.9 onwards.</a>
</br></br>
install libraries :
```bash
  $ python3 -m pip install opencv-python[gui] ultralytics roboflow
```

install my project :</br>
```bash
  $ git clone https://github.com/watcharapol28/Blurring-faces-and-vehicle-license-plates.git
```
</br>


## Running
To run the Blurring faces and vehicle license plate, follow these step :</br></br>
upload file videos that want to blur in the folder _"...\Blurring-faces-and-vehicle-license-plates\Test data\Videos\"_
</br></br>

open folder :
```bash
  $ cd Blurring-faces-and-vehicle-license-plates
```
change code in Blur_YOLO.ipynb (Input/Output path) to your videos name on `File name.File type` :

```py
  input_video_path = "...\Blurring-faces-and-vehicle-license-plates\Test data\Videos\[File name].[File type]"
  output_video_path = "...\Blurring-faces-and-vehicle-license-plates\Test data\Blurred\[File name].[File type]"
```


The results are stored in _"...\Blurring-faces-and-vehicle-license-plates\Test data\Blurred\"_</br>
</br></br>
