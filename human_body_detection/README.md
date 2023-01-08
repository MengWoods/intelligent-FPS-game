# Human body detection methods

Tried several methods, the skeleton detection is the one needed.

## Skeleton detection

1. MediaPipe pose estimation
    Good for near object but bad for far or small people recognition.
2. [MoveNet](https://blog.tensorflow.org/2021/05/next-generation-pose-detection-with-movenet-and-tensorflowjs.html)
   [Tutorial](https://www.tensorflow.org/hub/tutorials/movenet)



## Darknet YOLOv3


Only bounding box detected.

Reference: https://thedatafrog.com/en/articles/object-detection-darknet/

## HOG

[HOG_detection](HOG_detection.py) method is a low-level recognizition. For a simple case use. 

Reference: https://thedatafrog.com/en/articles/human-detection-video/
