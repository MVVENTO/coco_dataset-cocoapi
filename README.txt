COCO API - http://cocodataset.org/

COCO is a large image dataset designed for object detection, segmentation, person keypoints detection, stuff segmentation, and caption generation. This package provides Matlab, Python, and Lua APIs that assists in loading, parsing, and visualizing the annotations in COCO. Please visit http://cocodataset.org/ for more information on COCO, including for the data, paper, and tutorials. The exact format of the annotations is also described on the COCO website. The Matlab and Python APIs are complete, the Lua API provides only basic functionality.

In addition to this API, please download both the COCO images and annotations in order to run the demos and use the API. Both are available on the project website.
-Please download, unzip, and place the images in: coco/images/
-Please download and place the annotations in: coco/annotations/
For substantially more details on the API please see http://cocodataset.org/#download.

After downloading the images and annotations, run the Matlab, Python, or Lua demos for example usage.

To install:
-For Matlab, add coco/MatlabApi to the Matlab path (OSX/Linux binaries provided)
-For Python, run "make" under coco/PythonAPI
-For Lua, run “luarocks make LuaAPI/rocks/coco-scm-1.rockspec” under coco/


///////////////////////////////  ADDITIONAL RESOURCES /////////////////////////////////

COCO dataset guide ->
https://www.v7labs.com/blog/coco-dataset-guide

How to work with object detection dataset in COCO format ->
https://towardsdatascience.com/how-to-work-with-object-detection-datasets-in-coco-format-9bf4fb5848a4

How to train an Object Detector with your own COCO dataset in PyTorch ->
https://medium.com/fullstackai/how-to-train-an-object-detector-with-your-own-coco-dataset-in-pytorch-319e7090da5

Using COCO dataset & biases ->
https://datagen.tech/guides/image-datasets/ms-coco-dataset-using-it-in-your-computer-vision-projects/

COCO with YOLO tutorial ->
https://deeplodocus.readthedocs.io/en/master/tutorials/coco/

70 page Report : COCO dataset & Object Detection ->
https://hackernoon.com/70-page-report-on-the-coco-dataset-and-object-detection-part-2





