# FLS-segmentation
A lightweight FLS segmentation network. The network based on YOLOv8, contains the yaml file and weights file of the network. The dataset refer to the URL:https://www.kaggle.com/datasets/gaoxiansen93/forward-looking-sonar-obstacle-segmentation. Python>=3.8

## Files instructions
├── ReadMe.md           
    
├── test_model_type    // Yaml files of some test model
    
├── best.pt    // model weights file of ghost-YOLO for segmentation

├── ultralytics.zip    // Modified code files of YOLOv8


## Follow these two steps:

1.pip install ultralytics==8.2.36

2.pip installtorch==2.3.0
  
3.pip install torchvision==0.18.0

4.Replace the ultralytics folder by the zip file.
