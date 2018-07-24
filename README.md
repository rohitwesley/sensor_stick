# sensor_stick

### Exercise 1, 2 and 3 pipeline implemented :
#### 1. Complete Exercise 1 steps. Pipeline for filtering and RANSAC plane fitting implemented.
PointCloud Filtering with RANSAC - [RANSAC.py](https://github.com/rohitwesley/sensor_stick/blob/master/scripts/RANSAC.py)
![Object PointCloud](https://github.com/rohitwesley/sensor_stick/blob/master/images/object_pointcloud.png)

#### 2. Complete Exercise 2 steps: Pipeline including clustering for segmentation implemented.  
PointCloud Segmentation - [segmentation.py](https://github.com/rohitwesley/sensor_stick/blob/master/scripts/segmentation.py)
![Segmented](https://github.com/rohitwesley/sensor_stick/blob/master/images/color_cluster.png)

#### 3. Complete Exercise 3 Steps.  Features extracted and SVM(Support Vector Machine) trained.  Object recognition implemented.
Compute histograms :- [features.py](https://github.com/rohitwesley/sensor_stick/blob/master/src/sensor_stick/features.py)

Feature Generation :- [capture_features.py](https://github.com/rohitwesley/sensor_stick/blob/master/scripts/capture_features.py)

SVM Training :- [train_svm.py](https://github.com/rohitwesley/sensor_stick/blob/master/scripts/train_svm.py)

![Confusion Matrix](https://github.com/rohitwesley/sensor_stick/blob/master/images/confusion_matrix.png)
![Normalized Confusion Matrix](https://github.com/rohitwesley/sensor_stick/blob/master/images/normailzed_confusion_matrix.png)

Object Recognition :- [object_recognition.py](https://github.com/rohitwesley/sensor_stick/blob/master/scripts/object_recognition.py)

![Object Recognition](https://github.com/rohitwesley/sensor_stick/blob/master/images/object_recognition.png)
