This repository contains all the scripting done for the selfdriving picar. It's a school project that requires a picar to move between two white lines, this is done using 2 scripts. Host.py is the script that the picar needs, this contains the live video streaming and the receiving of commands. The client.py script contains the line detection functions, using cv2.

To execute the host.py script, install the following dependencies using pip:
numpy
io
logging
socketserver
http
threading
picamera2
flask
time
threading

For the client.py script, install the following dependencies using pip:
cv2
numpy
urllib.request
requests
time

For traffic light detection on laptop or pc:
Install yolov8 with pip3 install ultralytics
Install pytorch with pip3 install pytorch or pip3 install torch torch-vision opencv-python
Install labelme for labeling with pip3 install labelme
