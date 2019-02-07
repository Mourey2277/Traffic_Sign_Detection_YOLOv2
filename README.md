# Traffic_Sign_Detection_YOLOv2

For running the model Python3, tensorflow 1.0, numpy, opencv 3 and Cython needed.
It is recommended to use tensorflow-gpu to get better fps (frame per second). 
Download the folder from the google drive and turn on the command prompt from that folder then write the following command. 
The link of the google drive link is given below.

https://drive.google.com/drive/u/1/folders/0AOKQz5jIn7yLUk9PVA?ogsrc=32

If you are using tensorflow-gpu then write –gpu 0.7 other than that avoid that part only. 
In the command part testVideo refer to the video you want to test, and camera is referring to the web camera of the device.

Python steup.py build_ext –inplace

For testing in YOLOv2:
1) python flow --model cfg/yolov2-voc-22c.cfg --load 25125 --demo testVideo.mp4 --saveVideo
2) python flow --model cfg/yolov2-voc-22c.cfg --load 25125 --demo --demo camera

For Testing in tinyYOLO:
1) python flow --model Cfg/tiny-yolo-voc-22c.cfg --load 54500 --demo testVideo.mp4 --saveVideo
2) python flow --model Cfg/tiny-yolo-voc-22c.cfg --load 54500 --demo --demo camera
