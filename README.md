
# Widget Detector 


The Widget Detector employs deep learning to detect common user user interface components from hand drawn sketches. It then generates the necessary Flutter widget for that specific component. The purpose of this tool can speed up UI generation or even be used as a teaching tool.


By using TensorFlow, we implemented a two branch neural network, one for bounding box regression and one for widget label classification. In addition to that, we utilized transfer learning using the VGG16 pretrained model on ImageNet and added our two branch network on top of it.


[Update (07/25/2024)]

Used YOLOv9 for this approach. Link: https://github.com/aakashvardhan/s15-yolov9-project

Not implemented it with flutter yet.


Created by Aakash Madabhushi and Prince Hodonou


