# Abstract
License plate detection serves as one of the most widely-used real-world applications in fields like toll control, traffic scene analysis, and suspected vehicle tracking. Along with license plate information, to obtain overall comprehension, the information of the owner vehicle also plays a great role. We proposed a one-stage anchor-free object detector for detecting license plates and vehicles' poses with their regions. The detector, other than bounding boxes, gives bounding quadrilaterals, which gives a more precise indication for license plates. For single scale input, we reached license plate mAP/mAP50 of 35.4/82.3 on the benchmark dataset, already outperformed the existing commercial systems Open-ALPR and Sighthound. For multi-scale input, we reached the best mAP/mAP50 of 40.8/90.1. For the classification for the car pose (front or rear), we reached 98.8% accuracy, giving a promising result as an end-to-end license plate detector with contextual infor-mation.