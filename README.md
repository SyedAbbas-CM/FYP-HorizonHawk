# SkyGuardian: Autonomous Aerial Surveillance with Deep Learning

🚁 **SkyGuardian** is an advanced drone-based system designed for real-time object detection, tracking, and anomaly detection. Leveraging state-of-the-art deep learning models, SkyGuardian aims to revolutionize aerial surveillance, providing unparalleled insights and enhancing security measures across various environments.

## Features

- **Object Detection**: Accurately identify and locate objects such as humans, vehicles, and more.
- **Object Tracking**: Continuously monitor and track the movement of detected entities.
- **Anomaly Detection**: Instantly recognize and alert unusual or suspicious activities.

## Datasets & Models

- Utilizes datasets like COCO, VisDrone, UAVDT, and more.
- Employs models such as YOLO, SSD, Faster R-CNN, and DeepSORT for optimal performance.

-http://host.robots.ox.ac.uk/pascal/VOC/
-https://www.crcv.ucf.edu/data/UCF_Aerial_Action.php
-https://cvgl.stanford.edu/projects/uav_data/
-https://downloads.greyc.fr/vedai/
-https://gdo152.llnl.gov/cowc/
-http://xviewdataset.org/#dataset
-https://cemse.kaust.edu.sa/ivul/uav123
-https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery
-https://bozcani.github.io/auairdataset
-https://projects.asl.ethz.ch/datasets/doku.php?id=kmavvisualinertialdatasets
-https://github.com/VisDrone/DroneVehicle
-https://www.kaggle.com/datasets/gatewayadam/cars-and-tanks-image-classification
-https://www.kaggle.com/datasets/antoreepjana/military-tanks-dataset
-https://github.com/chaozhong2010/VHR-10_dataset_coco

-Object Detection: Explore models like YOLO, RetinaNet, and SSD. Train them on your datasets to detect humans, vehicles, and other objects of interest.
-Object Tracking: FairMOT is already a good choice. Additionally, consider exploring DeepSORT, which is mentioned in the papers above.
-Anomaly Detection: You'll need a separate model or approach to determine anomalous behavior based on the output from the tracking model.


## Deployment

- Optimized for edge computing on drones using devices like NVIDIA Jetson Nano & Xavier AGX.
- Capable of real-world deployment in diverse scenarios.
