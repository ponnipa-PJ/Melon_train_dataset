
Disease_Melons - v15 2021-04-01 11:34am
==============================

This dataset was exported via roboflow.ai on April 1, 2021 at 4:34 AM GMT

It includes 576 images.
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
* Random shear of between -23° to +23° horizontally and -23° to +23° vertically
* Random brigthness adjustment of between -25 and +25 percent
* Random exposure adjustment of between -28 and +28 percent
* Random Gaussian blur of between 0 and 2 pixels
* Salt and pepper noise was applied to 10 percent of pixels


