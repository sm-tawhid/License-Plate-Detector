# License Plate Detector

## Team Members
SM Tawhid – w211161582@student.hccs.edu

## Project Tier
Tier 1: Beginner Computer Vision project using Google Colab.  
This tier fits because it uses a single pre-trained YOLOv8 model for object detection with a small, publicly available dataset and minimal compute requirements.

## Problem Statement
Identifying vehicle license plates manually is slow and inconsistent.  
Traffic monitoring systems and parking management platforms need a fast, automated way to detect license plates accurately from images or video frames.

## Solution Overview
This project trains and evaluates a YOLOv8-based object detection model to automatically locate license plates in vehicle images.  
The model will draw bounding boxes around detected plates and measure accuracy using standard detection metrics.

## Technical Approach
CV Technique: Object Detection  
Model: YOLOv8  
Framework: PyTorch  
Why this approach: YOLOv8 provides a lightweight, high-accuracy object detector that can be fine-tuned easily in Google Colab using modest GPU resources.

## Dataset
Source: Roboflow Universe – License Plate Recognition Dataset  
Size: 10,125 images  
Labels: Single class (“license_plate”)  
Link: https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e

## Success Metrics
Primary Metric: mAP50  
Target: ≥ 0.85  
Secondary Metrics: Precision > 0.90 | Recall > 0.85 | Processing speed > 10 FPS (on Colab GPU)

## Week-by-Week Plan
Week 10: Finalize proposal and slides  
Week 11: Configure Colab + import dataset  
Week 12: Fine-tune YOLOv8n model  
Week 13: Evaluate results + visualize detections  
Week 14: Build demo notebook + record demo video  
Week 15: Present project + submit final repo

## Resources Needed
Compute: Google Colab Free GPU (Tesla T4)  
Cost: $0

## Risks & Mitigation
| Risk | Probability | Mitigation |
|---|---|---|
| Colab GPU runtime limit | Medium | Use YOLOv8n (small model) and save checkpoints often |
| Dataset imbalance	|	Medium | Apply image augmentation during training |
| Slow training speed	| Low |	Reduce epochs or batch size |

## AI Usage Log
This section will be updated throughout the project to document how AI tools were used throughout the project.

## Current Status
Repository created ✅  
Proposal written ✅  
Dataset acquired ✅  
Model training started  
Demo created  
Final presentation ready
