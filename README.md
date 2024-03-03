What does this repository help achieve?
Using these files an individual can detect 91 objects in realtime by accessing the desired camera of preference for realtime video output.  


You can use a local environment on pycharm or visual code.
Be sure to have python installed on your device and then the neccessary libraries to be installed on pycahrm or VS code. 
The file "ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt" contains the architecture and configuration details of an SSD MobileNetV3 model trained on the COCO dataset.
The "coco.names" file contains the names of all objects that can be detected by this pre-trained model. 
The file "frozen_inference_graph.pb" refers to a trained neural network model that has been converted into a format suitable for inference, where the model's parameters (weights and biases) are fixed.
Lastly, the main file accesses the specified camera for realtime object detection. 
Note: In order to change the camera to be selected, substitute "0" for "a" in cap = cv2.VideoCapture(a) to access inbuilt device webcam, and "1" to access externally connected type A webcam. 
