# Jaw-degradation-detection

This project is part of the Neural Networks course held by the University of Tartu. The aim of the project was to detect jaw degradation using object detection models trained on the [Panoramic Dental X-rays With Segmented Mandibles](https://data.mendeley.com/datasets/hxt48yk462/2). The images were manually annotated and cropped by other project members.

This code was used to train the [YOLOv5](https://github.com/ultralytics/yolov5) object detection model on the dataset. The image crops were augmented and preprocessed using [Roboflow API](https://roboflow.com). The cropped images with annotation files can be found in ```Jaw_degradation``` folder.

This code implementation was based on [guide](https://github.com/ultralytics/yolov5/wiki/Train-Custom-Data) made by Ultralytics. For a detailed project description and obtained results, visit our [blogpost](https://medium.com/@lastovko1997/recognition-of-jaw-degradation-on-x-rays-fac3567c48c9).
