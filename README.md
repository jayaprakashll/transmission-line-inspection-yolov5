(https://github.com/coldheartboy/transmission-line-inspection-yolov5/blob/d14208a3807b912da50522a1fbe63fd7b5332579/transmission%20line%20inspection%20using%20yolov5/insulators.jpg)
# transmission-line-inspection-yolov5
Trained a yolov5 with available dataset in roboflow thanks for the public dataset 
#Project Overview
The Transmission Line Inspection project focuses on automating the inspection of transmission lines, with a specific emphasis on detecting and analyzing insulators. This project utilizes the YOLOv5 (You Only Look Once) object detection framework to efficiently and accurately identify insulators along the transmission lines.


# to run the file 
step1 : install the requirement files
=> pip install -r requirements.txt


after installing the dependineces just use the below commadn to run
=> python3 detect.py --weights tweight.pt --source 0

for source 0 - it will use the web camera
