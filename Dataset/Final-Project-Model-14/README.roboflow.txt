
Final Project Model - v14 2023-05-11 2:31pm
==============================

This dataset was exported via roboflow.com on February 20, 2024 at 11:23 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 4446 images.
Legos are annotated in COCO format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)
* Auto-contrast via contrast stretching

The following augmentation was applied to create 3 versions of each source image:
* Random brigthness adjustment of between -34 and +34 percent
* Random exposure adjustment of between -10 and +10 percent
* Salt and pepper noise was applied to 2 percent of pixels


