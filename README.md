# Fundus-Vascular-Segmentation
This is our Biomedical Image Processing Course Project, we(Ruiyang Zhao, Xingyu Liu, Shenbo Gong) implemented three different segmentation methods (indicated below) and built GUI.

## Methods
1. Morphology +Region Growth. Code can be found in [./Morphology+Region Growth](https://github.com/charlotte12l/Fundus-Vascular-Segmentation/tree/master/Morphology%2Bregion%20growth)

- Applied morphology and bit plane slicing to get the shape and orientation map of blood vessels 
- Used the first Gaussian filter to mark the centerline; Combined the map and centerline using region-growing algorithm. 
- Achieved 0.956 Accuracy, 0.732 Sensitivity and 0.978 Specificity 

2. Deep learning method. We employed open source [code](https://github.com/DeepTrial/Retina-VesselNet)

- Used DenseUNet for segmentation. 
- Achieved 0.953 Accuracy, 0.931 Sensitivity and 0.955 Specificity

3. Match Filtering + Region Growth. Code can be found in [./Match Filtering+Region Growth](https://github.com/charlotte12l/Fundus-Vascular-Segmentation/tree/master/match%20filtering%2Bregion%20growth)
- Used match filtering and region-growing algorithm. 
- Achieved 0.951 Accuracy, 0.684 Sensitivity and 0.977 Specificity

## Results
- Input & GroundTruth

![](https://github.com/charlotte12l/Fundus-Vascular-Segmentation/blob/master/Input.png)

- Our Methods

![](https://github.com/charlotte12l/Fundus-Vascular-Segmentation/blob/master/Result.png)

