# Dataset Information – License Plate Detector

## Dataset Overview
Name: License Plate Recognition Dataset  
Source: Roboflow Universe – Workspace hcc-0e4mo  
Link: https://universe.roboflow.com/hcc-0e4mo/license-plate-recognition-rxg4e-samkt

## Dataset Details
Total Images: ~10,125  
Labels: Single class – license_plate  
Annotation Format: YOLOv8 TXT format 

## Data Splits:
70% Training  
20% Validation  
10% Testing  

## Load Dataset in Google Colab
The dataset can be downloaded automatically using the Roboflow API.  
Paste the following snippet into your Colab notebook:  
```python
!pip install roboflow  

from roboflow import Roboflow
rf = Roboflow(api_key="xcLpLcov5S0yjHXlnRgK")
project = rf.workspace("hcc-0e4mo").project("license-plate-recognition-rxg4e-samkt")
version = project.version(1)
dataset = version.download("yolov8")
