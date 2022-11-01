#yolo2-object-detection  
#do multi-object detection with yolo.h5  
#if you want to work with single object detection, you should first change the list voc_classes in yad2k.models.keras_yolo.py to one element list like this voc_classes=['horse']. Then modify yolo.cfg in line 237 and line 244: filters=30, classes=1. Finally, use command "python yad2k.py yolo.cfg yolo.weights model_data/yolo_single.h5" to generate a new model.
