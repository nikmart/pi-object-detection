# Realtime object detection on Raspberry Pi

#### Based on tutorial from PyImageSearch: [https://www.pyimagesearch.com/2017/10/16/raspberry-pi-deep-learning-object-detection-with-opencv/]

## Instructions

0. [if using pi headless, `ssh -X user@hostname` to use X11 forwarding
1. `git clone https://github.com/nikmart/pi-object-detection.git`
2. `cd pi-object-detection`
3. `pip3 install imutils`
4. `python3 realtime_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel`
5. On the GUI window git `q` to quit
6. `python3 people_counter.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel`
