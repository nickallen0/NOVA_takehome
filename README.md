![header-seedlings](https://github.com/nickallen0/NOVA_takehome/assets/45595516/4cf3dfed-db99-42f3-b219-875d494e8ce1)
# NOVA Deep Learning seedling detector 🔎🌲🗺️
<img width="212" alt="UAV-map-locations" src="https://github.com/nickallen0/NOVA_takehome/assets/45595516/618cb796-2c15-4140-ac4e-c45c9aff7d45">

Creating and testing YOLO seedling detectors for UAV imagery, using different training data.
Made by Nicholas Allen for NOVA summer course in As, Norway 2023. 

# Models 🕵️🍑
![banner-yolov8](https://github.com/nickallen0/NOVA_takehome/assets/45595516/f164222e-d3d1-4b14-bb36-0e0493d826d4)
Custom YOLO object detection implemented in Ultralytics were created from remotely sensed UAV imagery at 4 sites in Norway over 2023. Four models were created comprising the following:
- A nano sized YOLO trained on a small subset (11 images of 10x10m) of the data
- A medium sized YOLO trained on a small subset (11 images of 10x10m) of the data
- A nano sized YOLO trained on the dataset annotated by the whole class (144 images of 10x10m)
- A medium sized YOLO trained on the dataset annotated by the whole class (144 images of 10x10m)

This combination should allow us to test accuracy of model sizes, and training dataset sizes when creating object detection models.

# Results 📈💰
![yolo-compare](https://github.com/nickallen0/NOVA_takehome/assets/45595516/ebdeafea-47c9-4fc4-b4ba-35d29b7d48ba)
An indepth review of the performance can be viewed in the document found [here.](https://newcastle-my.sharepoint.com/:w:/g/personal/c0062193_newcastle_ac_uk/EfQ2mx4XNSxAqEuHYFTkcF8BCEF6CsrMam9mY3tl9h1tcw?e=jSPRiC)

