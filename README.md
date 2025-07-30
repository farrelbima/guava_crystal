
# Crystal Guava Fruit Quality Detection Using CNN

This project demonstrates a real-time guava crystal fruit quality detection using the Convolution Neural Networks (CNN). The model will be deployed to ESP32-CAM with the help of Edge Impulse.

The notebook guides users through the dataset preparation, model training, validation, deployment, and inference stages for detecting the guava crystal fruit quality.


## Background

Fruit quality is essential in the agricultural and trade industries, as fruit that does not meet standards can lead to significant economic losses and environmental impacts. Traditional methods of assessing fruit quality that rely on manual inspection are often inefficient and prone to errors. With the increasing global demand for food production, more effective solutions are needed. This project utilizes deep learning, in particular CNN, through image classification to detect fruit quality in real-time. A dataset of top-view images of crystal guava with classes consists of grade_a, grade_b, and grade_c fruit qualities.
## Outline
* Dataset Preparation
    * A brief explanation of the guava crystal dataset
    * Dataset training and validation split
    * Image data preprocessing 

* Training and Evaluating the Model
    * Initiating the training process 
    * Evaluating the model performance

* Model Deployment and Inference 
    * Conversion to TensorFlow Lite
    * Deployment to Edge Impulse
    * Inference with ESP32-CAM
## Libraries

```
- tensorflow
- sklearn
- numpy
- matplotlib
```

## Required Software and External Resources

Before you begin, make sure you have the following installed or accessible:

- [Edge Impulse](https://www.edgeimpulse.com/) – for model deployment.
- [Arduino IDE](https://www.arduino.cc/en/software) – for programming the microcontroller/ESP32-CAM.
- [OBS Studio](https://obsproject.com/) – for video streaming.

## Setup

* Make an environment with ```python==3.8.20``` using the following command

```conda create -n my_env python==3.8.20```

* Activate the environment

```conda activate my_env```

* Install the dependencies of the project using the following command

```pip install -r requirements.txt```
## Demo

