# mmWave-Radar-Relocalization
## Introduction
This is a dataset for relocalization based on millimeter wave (mmWave) radar point clouds. 

## Data Description
The dataset contains mmWave radar point clouds and pose groundtruth collected under 11 different scenes. Each scene contains 2-3 sequences collected alone similar routes. The dataset can be used for relocalization based on mmWave radar point clouds.

For a sequence of n frames, the data includes:

```
data_x.txt       (n lines, each line has x coordinates of m points)
data_y.txt       (n lines, each line has y coordinates of m points)
data_z.txt       (n lines, each line has z coordinates of m points)
data_i.txt       (n lines, each line has intensity values of m points)
data_label.txt   (n lines, each line is the pose groundtruth of the frame)
data_yaw.txt     (n lines, each line is the yaw groundtruth of the frame)
```
