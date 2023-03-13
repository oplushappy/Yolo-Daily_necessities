#### Yolo trash

### My goal
1. Use different yolo model to train and compare the effect of detect
2. Practice setting the hyperparamter
3. Understand how to use different yolo 
4. How to select Transfer Learning weigh
5. make more time trian vs make a big trian

### DataSet
I use GPU-3060 to train , so I use only 1500 picture dataset
Which comes from : <https://universe.roboflow.com/collect/c-as77e/dataset/5>
classify:
1. Bottle
2. Cup
3. Paper

### How to use 
- YOLO V5
1. download dataset and [yolo v5](https://github.com/ultralytics/yolov5/tree/v5.0)
2. change --weights = xxx.pt
3. --source xxx.image(you want to detect)

  - result:
  I think base on coco weight not good 
  - reason:
  1. The data too small
  2. transfer learning weight 
  
 
