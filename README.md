# FaceEmotion

This is a python script that perform Emotion Recognition while face tracking people.

This script is used with a GummiArm robot where a 2 dofs head gaze toward people's face.

## Emotion Recognition

The emotion recognition is based on the great post : https://sefiks.com/2018/01/10/real-time-facial-expression-recognition-on-streaming-data/

Keras and TensorFlow are used to train the face emotion recognition dataset https://www.kaggle.com/deadskull7/fer2013

.json and .h5 are the parameters of the model trained with different epochs. The more stable parameters seem the be with 15 epochs.

## ROS Head Tracking

The face tracking is the same code as here : https://github.com/rouzinho/FaceTracking 

