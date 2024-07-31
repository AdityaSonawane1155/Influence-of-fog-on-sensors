# Influence-of-fog-on-Lidar and Radar sensors
LiDAR and RADAR are active sensors. Active sensors provide their own source of energy to illuminate
the objects they detect. LiDAR detects objects by using a laser beam, and RADAR detects object
using electromagnetic waves. These sensors produce point cloud data, which can be used to detect
objects and their distance from the sensors. In this task, we are looking into three senors namely:
1. Velodyne Puck
2. Blickfeld Cube 1
3. MMWAVCAS-RF-EVM RADAR


Methodologhy: 
The method used to determine the influence of fog on the sensors is done by determining the distance
of the point cloud in 3-D space. The visualisation of distance from the sensor and corresponding
point cloud is done by using a Python script to plot a histogram. The dataset is in the form of .csv
files, which contains point cloud data under clear and fog conditions. The distance is calculated by
substituting the x,y, and z coordinates into the following formula:
Distance =
p
x
2 + y
2 + z
2
The operation of unwrapping the .csv files and calculating the distance is done by using the Numpy
library. The distance obtained is then plotted against the point cloud in the form of a histogram using
the Matplotlib library. The histograms obtained are then visually compared with respect to point
clouds present at respective distances in clear and fog conditions.
