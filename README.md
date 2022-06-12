# ML
Containing dataset, machine learning model, and supporting resources

## About

- Audio
  - Dataset and model for audio recognition for four kinds of violence.
- Image
  - Dataset and model for image recognition for violence detection.

## Dataset sources
This application allows you to:
- Audio
  - Violence Identification Audio Dataset (https://github.com/B21-CAP0175/violence-identification-tensorflow/tree/master/dataset)
- Image
  - Violence Identification Image Dataset (https://www.kaggle.com/datasets/karandeep98/real-life-violence-and-nonviolence-data)

## Model
[<img src="/audio-model.jpg" align="left"
width="400"
hspace="10" vspace="10">](/screenshot/ss1.png)
[<img src="/image-model.jpg" align="center"
width="400"
hspace="10" vspace="10">](/screenshot/ss2.png)


## Tools and Librarios

- Python                       3.8.13
- Tensorflow                   2.8.0
- Librosa                      0.9.1

## Deployment
The models both audio and image models will be deployed by us on a mobile app platform hence we have two formats of them, the .h5 model for tensorflow use and .tflite model for tensorflow lite or mobile use. You can find the .h5 file in /audio and /image while the .tflite model is stored in /audio/tflite3 and /image/tflite.
