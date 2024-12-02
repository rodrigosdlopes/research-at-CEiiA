# Object Detection Model for Satellite Imagery
This repository contains the research's report conducted in my 3-months internship at CEiiA

- [View full report (10 pages article)](https://github.com/rodrigosdlopes/thesis-2024/Sentinel-2 Truck Detection.pdf](https://github.com/rodrigosdlopes/research-at-CEiiA/blob/main/Sentinel-2%20Truck%20Detection.pdf)


**Title:** *Truck Detection in Multispectral Satellite Imagery using YOLOv8 Model*

**Abstract**: This report presents an application of the You Only
Look Once (YOLO) algorithm for the detection of moving trucks
in multispectral satellite imagery captured by the Sentinel-2
mission. The global coverage and regular acquisition of Sentinel-
2 images constitute the two primary advantages over other
traffic monitoring methods. The project aims to contribute to
the field of Remote Sensing by utilizing YOLOv8, a state-of-
the-art deep learning model for Object Detection, to monitor
road truck traffic in the surroundings of Porto, Portugal. The
dataset is composed by 300 images from motorways featuring
at least one truck, captured on different days. The report
details the dataset construction, including the use of Sentinel-2
data and OpenStreetMap road data to isolate road regions and
improve model accuracy. Manual annotations were performed
using Roboflow to create YOLO-compatible bounding box labels,
used as ground-truth. The evaluation metric, Intersection over
Union (IoU), is used to compare the proposed approach with a
baseline method (developed by Fisser et Al. [1]). Our approach
achieved an IoU = 0.63 between its prediction boxes and the
annotated boxes, surpassing the result obtained by the baseline
(IoU = 0.16) The results show the effectiveness of YOLO in
detecting trucks in multispectral satellite imagery, positioning
it as the most efficient method for identifying trucks in Sentinel-2 images.

**Key Words:** Remote Sensing, YOLO, Sentinel-2, Truck Detection, Deep Learning
