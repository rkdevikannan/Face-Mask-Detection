# face-mask-detection
Face Mask Detection

Introduction:

Face mask detection is a simple model to detect face mask. Developed with OpenCV, Keras, TensorFlow and Deep Learning. Detects face masks in static images as well as in real-time video streams. 

Description:

Three python scripts:

train_mask_detector.py - Accepts input dataset and fine tunes MobileNetV2 upon it to create our mask_detector_model. A training history plot.png containing accuracy/ loss curves is also produced.

detect_mask_image.py - Performs face mask detection in static image.

detect_mask_video.py - Using your webcam , this script applies face mask detection to every frame in the stream.  

Data collection:

* Real-World Masked Face Dataset(RMFD)

* Kaggle Datasets

Output:

* Detecting faces in images /videos

* Extracting each individual face ROI

* Applying face mask classifier

* Integrating Face mask classifier with a website 
 
