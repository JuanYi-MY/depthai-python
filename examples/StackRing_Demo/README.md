# DEMO

This is an example of running model that had been trained in SSD-MobileNet-V2 with custom dataset.

## Description

The demo detects the stack rings (which had been trained) & sequence check if the rings are in correct sequence.
* [Link for post in Hackster.io](https://www.hackster.io/JuanYi/object-detection-using-oak-d-with-custom-dataset-ecc7f0)
* [Link for demo video](https://youtu.be/8Yuxpd92Ia4)

## Contains
* ```Roboflow_Deploy_Custom_Mobilenet_to_OAK-D - StackRing_R4_Public.ipynb``` for training custom dataset
* ```mobilenet-ssd-openvino_2012.3_6shave_StackRingR4.blob``` model file trained by custom dataset
* ```spatial_mobilenet_StackRingR4_6_Public.py``` for detecting the stack rings and sequence check
