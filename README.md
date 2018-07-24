# sensor_stick

### Filtering Steps:
1. Image
2. Voxel Grid Downsampling
3. Passthrough over Z-Axis
4. Passthrough over X-Axis
5. Outlier Filter
6. RANSAC PLANE Filter

### Exercise 1, 2 and 3 pipeline implemented :
#### 1. Complete Exercise 1 steps. Pipeline for filtering and RANSAC plane fitting implemented.
PointCloud Filtering with RANSAC - [RANSAC.py] (./scripts/RANSAC.py)
![Object PointCloud] (./images/object_pointcloud.png)

#### 2. Complete Exercise 2 steps: Pipeline including clustering for segmentation implemented.  
PointCloud Segmentation - [segmentation.py] (./scripts/segmentation.py)

![Segmented] (./images/color_cluster.png)

#### 3. Complete Exercise 3 Steps.  Features extracted and SVM(Support Vector Machine) trained.  Object recognition implemented.
Compute histograms :- [features.py] (./src/sensor_stick/features.py)

Feature Generation :- [capture_features.py] (./scripts/capture_features.py)

SVM Training :- [train_svm.py] (./scripts/train_svm.py)

![Confusion Matrix] (./images/confusion_matrix.png)
![Normalized Confusion Matrix] (./images/normailzed_confusion_matrix.png)

Object Recognition :- 
![Object Recognition] (./images/object_recognition.png)
