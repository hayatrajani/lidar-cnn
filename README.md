# LiDAR CNN

## An attempt to implement the approach proposed in "Learning Semantic Place Labels from Occupancy Grids using CNNs" by Goeddel and Olson 

### Abstract

The goal of this paper is to develop a robot with
a grounded spatial vocabulary. Such a vocabulary would allow
it to give and follow directions, and would give it valuable
additional information in aiding localization and navigation.
We approach the problem by defining an ontology of space
(including corridor, doorway, and room) and by creating a
Convolutional Neural Network (CNN) that allows the robot
to classify LIDAR sensor data accordingly. In particular, we
propose a CNN architecture that performs comparably or
better than existing methods based on engineered features.
Training CNNs can be fickle; we describe several specific aspects
of our approach that are important for good performance in
this task.

Goeddel, Robert, and Edwin Olson. "Learning semantic place labels from occupancy grids using CNNs." 2016 IEEE/RSJ international conference on intelligent robots and systems (IROS). IEEE, 2016.

#### Dataset and Trained Model available [here](https://drive.google.com/drive/folders/18Dt1mrC0Cco3dqkvO24Qh63-JuYNFU69?usp=sharing)
The dataset consists of about 75,000 images which were generated from 2D range scans captured in different environments. The range scans were obtained from the [datasets](http://www2.informatik.uni-freiburg.de/~omartine/place_data_sets.html) hosted by Oscar Martinez Mozos.
