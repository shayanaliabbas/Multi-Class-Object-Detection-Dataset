Multi-Class Object Detection Dataset

Description:

This repository features a custom-labeled dataset developed using the LabelImg tool for Computer Vision tasks. The dataset is optimized for training object detection models like YOLO, providing both raw images and high-precision bounding box annotations. It covers a variety of real-world scenarios, including urban traffic and nature, ensuring a diverse training environment.

Dataset Features:

Total Classes: 7 distinct categories.
Annotation Format: YOLO (.txt files).
Labeling Tool: LabelImg.
Precision: Tight bounding boxes focused on maximizing model localization accuracy.

Classes Included:

human
horses
flowers
dogs
cats
cars
bike

Project Structure:

/labeled_images: Contains the source images (PNG/JPG).
/labels: Contains the corresponding YOLO format annotation text files.
classes.txt: Defines the class indices for the model.
