# TensorFlow-2-Object-Detection-example

### About the notebook
--------------------------------------
- Object_Detection_in_TFLite__from_TensorFlow_2_Detection_Model_Zoo.ipynb colab notebook contains executable cells to load SSD models from [TensorFlow 2 Detection Model Zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md) create .tflite file and make inference with images with objects e.g fruits. Note that only SSD models can be converted at the moment.

### Output
--------------------------------------
If everything runs without problems the output will be:

<img src="detected_fruits.jpg" width="256" height="540">

### Acknowledgement
--------------------------------------
I would like to thank [Sayak Paul](https://github.com/sayakpaul) for his original notebooks and [github repo](https://github.com/sayakpaul/E2E-Object-Detection-in-TFLite) showing how to train a custom detection model with the TFOD API (TF2 and TF1), optimize it with TFLite, and perform inference with the optimized model.
