<!--

#################################################
### THIS FILE WAS AUTOGENERATED! DO NOT EDIT! ###
#################################################
# file to edit: 99_index.ipynb
# command to build the docs after a change: nbdev_build_docs

-->

# slicer

> Slice images/labels with overlapping and in different scales Predict (with fastai) and merge the sliced images to full size


## Feature

- Preprocess of high resolution imagery and label data for use in Semantic Segmentation tasks (Deep Learning)
- Increases amount of trainingdata by generating different scales and overlappings for images and labels
- Multi stage interpolation (Nearest Neighbor + Bicubic combined) for image data
- Nearest Neighbor interpolation for label data
- More than half empty slices will be ignored / It is possilbe to slice a dismembered Mosaik!
- Add padding (to the right and bottom) to your high resolution images
- Do fastai predictions and merge the images to full size

Docs under https://abalone1.github.io/slicer/
