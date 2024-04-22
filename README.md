# Object detection in images using pytorch

## Repository Overview

This GitHub repository hosts a series of Jupyter notebooks focused on object detection in images, offering practical implementations and insightful demonstrations in Python. Here's what each notebook covers:

| Notebook Name                        | Description                                                   |
|--------------------------------------|---------------------------------------------------------------|
| `General_Intersection_over_Union`               | Detailed implementation of the IoU and GIoU metrics. Essential for understanding these evaluation metrics in object detection models. |
| `Airplanes_Detection_wResnetAndRetinanet`  | Implements object detection using a custom model built using resnet50 and retinanet. This work is still in progress. The results have not been as expected.  |
| `Airplanes_Detection_wCustomYolo`            | Implements object detection using a custom YOLO (You Only Look Once) approach. This work is still in progress. The results have not been as expected. |

Each notebook is crafted to provide a hands-on experience with object detection techniques, from foundational metrics to advanced methodologies. Whether you are a beginner or an experienced practitioner, these notebooks serve as a valuable resource for understanding and applying object detection algorithms in real-world scenarios.


## Notebook: General_Intersection_over_Union.ipynb
### Intersection over Union (IoU)
IoU is a metric used in computer vision to measure the accuracy of an object detector on a particular dataset. It is defined as the area of overlap between the predicted bounding box and the ground truth bounding box, divided by the area of union of these two boxes:

IoU = Area of Overlap / Area of Union

### Generalized Intersection over Union (GIoU)

GIoU is an extension of the IoU metric, designed to offer a more accurate measure of the spatial relationship between two bounding boxes. It takes into account the cases where IoU is 0 (non-overlapping bounding boxes). GIoU is defined as:

GIoU = IoU - (Area of the Smallest Enclosing Box - Area of Union) / Area of the Smallest Enclosing Box
