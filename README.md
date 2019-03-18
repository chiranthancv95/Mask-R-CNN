Use mask_rcnn.py to detect objects in an image using computer vision.<br/>
The model used is Inception v2 Model and can classify upto 90 classes(Inception v2 is trained on COCO dataset). The classes used can be found in the file - object_detection_classes_coco.txt<br/>
The defaut confidence level is set to 0.5 and can be changed as required using the arg parameters.<br/>
The ROI, mask and Segment can be visualized by initializing the arg parameter to 1.<br/>
Usage - <br/>
1.python mask_rcnn.py --mask-rcnn mask-rcnn-coco --image images/example_01.jpg<br/>
2.python mask_rcnn.py --mask-rcnn mask-rcnn-coco --image images/example_03.jpg --visualize 1      <br/>
(For Visualization).
