This repository is used to store modified yolo v8

•**Modifications to YOLOv8** 

​    \- Modified Backbone to PP-LCNet

​    \- Modified PP-LCNet Architecture

​    \- Replaced Optimizer with Lion

The main files that have been modified are:

```
nn\modules\conv.py
nn\modules\block.py
cfg\models\v8\yolov8-PP-LCNet-rep-dp-rp.yaml
cfg\models\v8\yolov8-PP-LCNet-rep-dp.yaml
cfg\models\v8\yolov8-PP-LCNet-rep.yaml
cfg\models\v8\yolov8-PP-LCNet.yaml
```

This repository is an improvement on https://github.com/ultralytics/ultralytics