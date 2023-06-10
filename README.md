# Edge_AI_Final
Original repo: https://github.com/Linaom1214/TensorRT-For-YOLO-Series, https://github.com/WongKinYiu/yolov7 
## Create ENV
``` 
conda create -n <YOUR_ENV_NAME> python==3.10
pip install -r ./yolov7/requirement.txt
```
FOLLOW https://github.com/Linaom1214/TensorRT-For-YOLO-Series TO INSTALL TensorRT

## INFERENCE WITH EXAMPLE VIDEO WITHOUT TensorRT
```
python ./yolov7/detect.py
```

## INFERENCE WITH EXAMPLE VIDEO WITH TensorRT
```
python ./TensorRT-For-YOLO-Series/trt.py
```

## INFERENCE WITH YOUR DATA WITHOUT TensorRT
```
python ./yolov7/detect.py --weight <your_weight> --source <your_inference_video>
```

## INFERENCE WITH YOUR DATA WITH TensorRT

FOLLOW https://github.com/Linaom1214/TensorRT-For-YOLO-Series
