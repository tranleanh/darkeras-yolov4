# Darkeras: Executing YOLOv3/YOLOv4 Object Detection on Keras with Darknet Pre-trained Weights

[![Blog](https://img.shields.io/badge/Blog-Medium-blue)](https://towardsdatascience.com/darkeras-execute-yolov3-yolov4-object-detection-on-keras-with-darknet-pre-trained-weights-5e8428b959e2)

This project is to execute YOLOv3/YOLOv4 object detector on Keras using Darknet pre-trained weights.

## Dependencies
- OpenCV
- Tensorflow 2.3.0
- Keras 2.4.0
- Easydict
- Matplotlib

You can simply run:
```bashrc
$ pip install -r requirements.txt
```

## Supported Models
- YOLOv3
- YOLOv4

## How to Use

### 1. Run with Notebook
- Put pre-trained weights from official Darknet [website](https://pjreddie.com/darknet/yolo/) or your trained weights into "weights" folder (If you use your model trained on your customed dataset, please change NUM_CLASS and ANCHORS in the notebooks)
- Run YOLOv3: darkeras-yolov3.ipynb
- Run YOLOv4: darkeras-yolov4.ipynb

### 2. Run with Python Scripts
- Convert Darknet (format: weight_file.weights) to Keras (format: weight_file.h5): to be updated
- Run YOLOv3: to be updated
```bashrc
$ python detect_yolov3.py
```
- Run YOLOv4: to be updated
```bashrc
$ python detect_yolov4.py
```

## Detection Results
- Input
<img src="docs/kite.jpg" width="800">

- YOLOv3
<img src="docs/detections_yolov3.jpg" width="800">

- YOLOv4
<img src="docs/detections.jpg" width="800">


## Citation

Please cite this repo if it's helpful for your study. 

```bibtex
@misc{tran2021darkeras,
  author = {Tran, Le-Anh},
  title = {Darkeras: Executing YOLOv3/YOLOv4 Object Detection on Keras with Darknet Pre-trained Weights},
  year = {2021},
  publisher = {GitHub},
  journal = {GitHub repository}
}
```

Have fun!

LA Tran

August 2021
