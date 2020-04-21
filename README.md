# Blink_Detection
Blink detection (EORA Summer Internship)

## Prerequisites:
#### 1) python > 3.7 
#### 2) scipy 
#### 3) numpy
#### 4) opencv
#### 5) dlib
#### 6) shape_predictor_68_face_landmarks.dat or other possible pretrained models which are compatible with dlib and were built for face landmarks detection
## How to use:
### Actually you have two options of usage:
#### 1) Use the input video as an input and analyze for blinks
```python blink_detect.py -v input.mp4 --shape-predictor shape_predictor_68_face_landmarks.dat```
#### 2) Use your built-in camera for blink detection
```python blink_detect.py --shape-predictor shape_predictor_68_face_landmarks.dat```
