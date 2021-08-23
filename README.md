# Darkeras: Execute YOLOv3/YOLOv4 Object Detection on Keras with Darknet Pre-trained Weights

This project is to execute YOLOv3/YOLOv4 object detector on Keras framework with Darknet pre-trained weights.

Medium article: (will be updated)

### Dependencies
- OpenCV
- Tensorflow 2.3.0
- Keras 2.4.0

### Supported Models
- YOLOv3
- YOLOv4

### How to Use
- Put pre-trained weights from official Darknet [website](https://pjreddie.com/darknet/yolo/) or your trained weights into "weights" folder (If you use your model trained on your customed dataset, please change NUM_CLASS and ANCHORS in the notebooks)
- Run YOLOv3: darkeras-yolov3.ipynb
- Run YOLOv4: darkeras-yolov4.ipynb

### Detection Result
- Input
<img src="docs/kite.jpg" width="800">

- YOLOv3
<img src="docs/detections_yolov3.jpg" width="800">

- YOLOv4
<img src="docs/detections.jpg" width="800">




Have fun!

LA Tran

Korea, August 2021
