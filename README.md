# Licence-Plate-Detection-using-YOLO-V8

# Dataset
https://universe.roboflow.com/snu-i6ovv/license-plate-detector-ogxxg
Dataset useing Yolo V8 Online
!pip install roboflow
from roboflow import Roboflow
rf = Roboflow(api_key="**********") #Put your API Key here
project = rf.workspace("snu-i6ovv").project("license-plate-detector-ogxxg")
dataset = project.version(1).download("yolov8")
