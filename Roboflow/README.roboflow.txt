
Disease_Melons - v7 augmentaion
==============================

This dataset was exported via roboflow.ai on March 30, 2021 at 8:11 AM GMT

It includes 546 images.
Melons-Leaf are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Randomly crop between 0 and 20 percent of the image
* Random rotation of between -15 and +15 degrees
* Random shear of between -15° to +15° horizontally and -15° to +15° vertically
* Random brigthness adjustment of between -25 and +25 percent
* Random exposure adjustment of between -25 and +25 percent
* Random Gaussian blur of between 0 and 1.75 pixels
* Salt and pepper noise was applied to 5 percent of pixels


