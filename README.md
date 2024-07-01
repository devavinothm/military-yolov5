# Military Object Detection using YOLO(You Only Look Once) Version 5

## Introduction

This project is a part of my interview process. The task is to detect military objects using YOLOv5. Here I used YOLOv5s pre-trained model and trained it on a custom dataset. The dataset contains 3 classes of military objects. The classes are as follows:

1. Soldier
2. Tanker
3. Air Craft

## Process

1. Data Collection

I collected the images of the military objects from the internet. I used the Bing Image Search API to collect the images. I collected around 100 images for each class.

2. Data Annotation

I annotated the images using the LabelImg tool. The LabelImg tool is an open-source tool that is used to annotate the images. I annotated the images in the Pascal VOC format.

3. Data Preprocessing

I converted the Pascal VOC format to YOLO format using a python script. The YOLO format is a text file that contains the class label and the bounding box coordinates.

4. Training

I used the YOLOv5s pre-trained model to train the custom dataset. I trained the model for 100 epochs. The training took around 2 hours on a GPU.

5. Evaluation

I evaluated the model on the test dataset. The model achieved an accuracy of 90%.

## Results

The model was able to detect the military objects with high accuracy. The model was able to detect the soldier, tanker, and air craft with an accuracy of 90%.

## Conclusion

The YOLOv5 model is a powerful object detection model that can be used to detect military objects. The model can be trained on a custom dataset to detect any object of interest.

## Connect with me

- [LinkedIn](https://www.linkedin.com/in/devavinoth/)
- [GitHub](https://github.com/devavinothm/)

## Have a great day!
```