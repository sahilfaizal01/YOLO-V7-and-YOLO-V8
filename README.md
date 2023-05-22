# YOLOv7-and-YOLOv8
This repository contains projects and learning materials of the object detectors YOLOv7 and YOLOv8
# What is YOLO?
* Joseph Redmon, Santhosh Divala, Ross Girshick, and Ali Farhadi introduced YOLO (You Only Look Once).
* YOLO gained popularity because of its accuracy while maintaining a small model size.
* From versions 1-4 YOLO was maintained in a C code in a custom deep learning framework written by Redmon called Darknet.
* In the last two years YOLOR, YOLOX, YOLOv6 and YOLOv7 emerged around the world, out of their own PyTorch based implementations. 
* Each model has brought new SOTA techniques that continue to push model accuracy and efficiency.
* Maintains small model size and can be trained on a single GPU as well.
# What is YOLOv8?
* The latest version of YOLO, YOLOv8 was released on January 10, 2023, claiming advancements in structure and architectural changes with better results.
* YOLOv8 is the newest state of the art YOLO model that can be used for object detection, image classification and instance segmentation tasks.
* In YOLOv8 the issue of prolonged training is somewhat addressed.
* The tradeoff between training time and precision is achieved more in YOLOv8.
# Key Features of YOLOV8
* The key features of YOLOv8 is its Extensibility, it is desgined as a framework that supports all previous versions of YOLO, making it easier to switch between different versions and compare their performance.
* YOLOv8 includes a new back bone network, a new anchor free detection head and a new loss function.
* YOLOv8 is highly efficient and can run on variety of hardware platforms, from CPUs to GPUs.
* Anchor free detections are faster and more accurate than previous versions.
# What are the reasons for using YOLOv8?
* YOLOv8 has a high rate of accuracy measured by COCO and Roboflow (COCO is the benchmark that people usually use in object detection)
* YOLOv8 outperforms other YOLO models in terms of speed and accuracy, the Mean Average Precision of 53.7 has been marked.
* YOLOv8 can be installed in two ways from the source and via pip. This is because it is the first iteration of YOLO to have an official package.
* New backbone network, new anchor free detection head and new loss function makes things much faster.
* YOLOv8 does not predict based on bouding box anchors which is what the other models used to do.
