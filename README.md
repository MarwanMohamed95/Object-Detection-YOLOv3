# **YOLO V3 (You Only Look Once)**


![p](https://github.com/MarwanMohamed95/YOLO-V3/blob/main/result1.gif)

In this Project, we will develop a YOLOv3 model for object detection on new photographs.

The "You Only Look Once" or YOLO, family of models are a series of end-to-end deep learning models designed for fast object detection, developed by Joseph Redmon

The approach involves a single deep convolutional neural network that splits the input into a grid of cells and each cell directly predicts a bounding box and object classification. The result is a large number of candidate bounding boxes that are consolidated into a final prediction by a post-processing step.

We will use ![keras-yolo3: Training and Detecting Objects with YOLO3 Reposetory](https://github.com/experiencor/keras-yolo3) scripts to convert the pre-trained weights into Keras format, use the pre-trained model to make predictions, and provided the code required to distill interpret the predicted bounding boxes.

In this project we will make object detection using two methods:

  - The first one is by applying the inference from scratch keras-yolo3: Training and Detecting Objects with YOLO3 Reposetory.
  - The second one is by using darknet framework which include alot of pretrained models and yolov3 is one of them.


## YOLOv3 model architecture

![model](https://github.com/MarwanMohamed95/YOLO-V3/blob/main/yolov3_network.png?raw=true)

## Some Results of the model 

#### From Scratch Result                                                                 |   Darknet Result           
![scratch](https://github.com/MarwanMohamed95/YOLO-V3/blob/main/out_cars1.png?raw=true)  |  ![darknet](https://github.com/MarwanMohamed95/YOLO-V3/blob/main/out_cars2.png?raw=true)

![j](https://github.com/MarwanMohamed95/YOLO-V3/blob/main/result2.gif)