# Face Recognition using Haar-Cascade Classifier, OpenCV, and Python
Simple Face Recognition algorithm using Python and OpenCV

## Requirements
- Python 3.5+
- OpenCV 3.1.0
- Numpy

## Outline
This project consist of 3 parts, which are:
1. Creating datasets (face_datasets.py)
2. Train the model (training.py)
3. Face Recognition (face_recognition.py)

## How to run ?
1. Make sure have executable permission. (chmod 777 .)
2. Remove the post-it note from your webcam.

Add a person
1. Run `python face_datasets.py` to add images. Two directories 'datasets' and 'trainer' will be created in the project directory. 'dataset' should populate with the images.
2. Train your datasets by running `python training.py`. 
3. Lastly, run `python face_recognition.py`


Add additional people
1. Change the variable "face_id = 1" to "face_id = 2" in (face_datasets.py: line 23) and re-run `python face_datasets.py`
2. `python training.py`
3. `python face_recognition.py`
4. You can change the 'Id' to match user's name (face_recognition: line 62):         
        ex). `if (Id == 1):
            Id = "User1"` to `if (Id == 1):
            Id = "Bill"`

## TroubleShooting
if you get an error try:
- `pip install opencv-contrib-python`
- `pip install opencv-python`

- Depending on how python is configured on your machine, you may need to use `python3` and `pip3` instead of `python` and `pip` when running the scripts

![alt text](https://github.com/410dood/Face-Recognition/blob/master/demo1.gif?raw=true "Logo Title Text 1")

##### Credit to:
Anirban from TheCodacus. Link: http://thecodacus.com/
All rights reserved to the respective owner
