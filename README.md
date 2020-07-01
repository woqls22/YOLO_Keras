# YOLO_Keras
YOLO Darknet모델을 Keras모델로 변환하였음

## YOLO v3 weight 다운로드 [https://pjreddie.com/darknet/yolo/]

## 모델 변환
$ python convert.py yolov3.cfg yolov3.weights model_data/yolo.h5 

## 사용
$ python yolo_video.py --input test.mp4

## 환경
Python 3.5.2
Keras 2.1.5
tensorflow 1.14.0

