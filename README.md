# Face Mask Detection
Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.

# 🔑 Prerequisites
tensorflow
keras
imutils
numpy
opencv-python
matplotlib
scipy

# 🔑 Results
We got the following accuracy/loss training curve plot
![plot](https://user-images.githubusercontent.com/83828452/140905167-9af7f67f-390c-4b60-a11e-fee44c96029e.png)

# Images
![1](https://user-images.githubusercontent.com/83828452/140905313-712cc3b4-251d-49b1-81b6-675c25e48651.png)
                                              
                                              With mask
 ![2](https://user-images.githubusercontent.com/83828452/140905419-80676471-6d0a-4b2e-ad60-a19069617ffe.png)

# Internet of Things Device Setup
Expected Hardware
Raspberry Pi 4 4GB with a case
5MP OV5647 PiCamera from Arducam
Getting Started
Setup the Raspberry Pi case and Operating System by following the Getting Started section on page 3 at documentation/CanaKit-Raspberry-Pi-Quick-Start-Guide-4.0.pdf or https://www.canakit.com/Media/CanaKit-Raspberry-Pi-Quick-Start-Guide-4.0.pdf
With NOOBS, use the recommended operating system
Setup the PiCamera
Assemble the PiCamera case from Arducam using documentation/Arducam-Case-Setup.pdf or https://www.arducam.com/docs/cameras-for-raspberry-pi/native-raspberry-pi-cameras/5mp-ov5647-cameras/
Attach your PiCamera module to the Raspberry Pi and enable the camera
Raspberry Pi App Installation & Execution
Run these commands after cloning the project

Commands	Time to completion
sudo apt install -y libatlas-base-dev liblapacke-dev gfortran	1min
sudo apt install -y libhdf5-dev libhdf5-103	1min
pip3 install -r requirements.txt	1-3 mins
wget "https://raw.githubusercontent.com/PINTO0309/Tensorflow-bin/master/tensorflow-2.4.0-cp37-none-linux_armv7l_download.sh"	less than 10 secs
./tensorflow-2.4.0-cp37-none-linux_armv7l_download.sh	less than 10 secs
pip3 install tensorflow-2.4.0-cp37-none-linux_armv7l.whl	1-3 mins 

