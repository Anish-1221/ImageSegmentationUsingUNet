# ImageSegmentationUsingUNet

The dataset zip file consists of 2 zip files, one for train and one for test that need to be unzipped.

Each folder in the train dataset belongs to one image. Each of those folders have 2 sub folders, the one named "images" is the image itself.
The folder named "masks" consists of multiple images with each image segmenting one cell. This folder is our dependent variable while training the model.

We use UNet in order to perform the segmentation of the cells.
