# YOLO-Object-Detection
## What is YOLO v2 (aka YOLO 9000)
YOLO9000 is a high speed, real time detection algorithm that can detect on OVER 9000! (object categories)

## Step1 - Requirements
- Python 3.5 or 3.6
- Tensorflow (tutorial GPU verions https://www.youtube.com/watch?v=RplXYjxgZbw&t=91s)
- openCV (https://www.lfd.uci.edu/~gohlke/pythonlibs/)

## Step2 - Download the Darkflow repo
https://github.com/thtrieu/darkflow

Extract the files somewhere locally

## Step3 - Build the library
Open an cmd window and type
python setup.py build_ext --inplace

OR

pip install -e .

## Step 4 - Download a weights file
Download the YOLOv2 608x608 weights file here (https://pjreddie.com/darknet/yolo/)

NOTE: Put the wights file in the bin folder.
