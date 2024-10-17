# Hand Gesture Recognition with YOLOv8

## Introduction
This project aims to develop a real-time hand gesture recognition system using the YOLOv8 object detection framework. The system can recognize five different hand gestures: peace, fist, and three other custom gestures. The model is trained on a custom dataset collected using a webcam.

## Dataset
The dataset used for training and testing the model is named `custom-data.ipynb`. The dataset consists of images of hands performing different gestures. The images were collected using a webcam and manually annotated with bounding boxes.

## Model
The YOLOv8 model was used for object detection. YOLOv8 is a state-of-the-art, one-stage object detection model known for its speed and accuracy.

## Training
The model was trained using the `train-model.ipynb` script. The training process involved fine-tuning the pre-trained YOLOv8 weights on the custom dataset. The following hyperparameters were used:


## Testing
The trained model was evaluated on a separate test set using the `test_model.ipynb` script. 

