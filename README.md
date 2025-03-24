# AeroZeno
Msc. Aerial Robotics Group Project
Autonomous Aerial Wildlife Survey and Payload Delivery

This project aims to develop and evaluate an autonomous aerial system capable of wildlife detection and targeted payload deployment using computer vision and waypoint-based drone navigation.

The included Python Notebook contains all the source code used in this project.

Notebook Sections:
- FOR VIDEO: Runs inference on full aerial survey videos using YOLOv8.
- FOR IMAGE: Performs detection on individual aerial images.
- TO GET FRAMES FROM VIDEO: Extracts frames from recorded flight videos for training and evaluation.
- VIDEO WITH QUADRANT INFORMATION: Annotates detection results with quadrant position for payload decision-making.
- IMAGE WITH QUADRANT INFORMATION: Similar to above, but for still images.
- CODE FOR MISSION (YET TO BE TESTED): Placeholder for autonomous payload release logic based on quadrant detection.

Trained Models:
- **Train4**: Early YOLOv8 model trained on a preliminary dataset.
- **Train8**: Final trained YOLOv8 model used for field testing and evaluation.
Both models are included for testing and comparison.

Instructions:
1. Open the Jupyter Notebook (`.ipynb`) in a Python environment (e.g., JupyterLab, VS Code).
2. Follow the notebook sections sequentially.
3. Ensure all required folders (e.g., images/, videos/, runs/, models/) and weights (Train4.pt, Train8.pt) are in the working directory.


Authors:
Thejas Thomson  
Sai Pavan
Nitin
Ming Ye
Swapnil
University of Bristol – Aerial Robotics Group
