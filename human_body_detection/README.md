# Human body detection methods

Tried several methods, the skeleton detection is the one needed.

## Skeleton detection

1. MediaPipe pose estimation
    Good for near object but bad for far or small people recognition.
    [example](../resources/cf-skeleton-recognition-mediapipe.gif)


## Darknet YOLOv3


Only bounding box detected.

Reference: https://thedatafrog.com/en/articles/object-detection-darknet/


## HOG

[HOG_detection](HOG_detection.py) method is a low-level recognizition. For a simple case use. 

Reference: https://thedatafrog.com/en/articles/human-detection-video/
