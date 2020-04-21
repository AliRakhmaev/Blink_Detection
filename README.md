# Blink_Detection
Blink detection (EORA Summer Internship)

## Prerequisites:
python > 3.7 
scipy 
numpy
opencv
dlib
shape_predictor_68_face_landmarks.dat or other possible pretrained models which are compatible with dlib and were built for face landmarks detection 
## How to use:
# Actually you have two options of usage:
# 1) Use the input video as an input and analyze for blinks
```python blink_detect.py -v input.mp4 --shape-predictor shape_predictor_68_face_landmarks.dat```
# 2) Use your built-in camera for blink detection
```python blink_detect.py --shape-predictor shape_predictor_68_face_landmarks.dat```
