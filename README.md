# Influence-of-fog-on-Lidar and Radar sensors
The overall aim of this work is to explore how fog affects sensor measurements. This involves analyzing data collected from three different sensors in varying conditions. LiDAR and RADAR are active sensors. Active sensors provide their own source of energy to illuminate
the objects they detect. LiDAR detects objects by using a laser beam, and RADAR detects object
using electromagnetic waves. These sensors produce point cloud data, which can be used to detect
objects and their distance from the sensors. In this task, we are looking into three senors namely:
1. Velodyne Puck
2. Blickfeld Cube 1
3. MMWAVCAS-RF-EVM RADAR



Methodology:                                                                                              
The method used to determine the influence of fog on the sensors is done by determining the distance
of the point cloud in 3-D space. The visualisation of distance from the sensor and corresponding
point cloud is done by using a Python script to plot a histogram. The dataset is in the form of .csv
files, which contains point cloud data under clear and fog conditions. 

The operation of unwrapping the .csv files and calculating the distance is done by using the Numpy
library. The distance obtained is then plotted against the point cloud in the form of a histogram using
the Matplotlib library. The histograms obtained are then visually compared with respect to point
clouds present at respective distances in clear and fog conditions.


![Screenshot 2024-07-31 223414](https://github.com/user-attachments/assets/ee8071c8-0083-4a55-ae3a-bc5b028ac730)
![Screenshot 2024-07-31 223433](https://github.com/user-attachments/assets/ccc6d574-ce09-4bc3-8e06-342ad8407607)
![Screenshot 2024-07-31 223442](https://github.com/user-attachments/assets/4e229324-bb3e-403a-a187-0b37c1a10411)
![Screenshot 2024-07-31 223450](https://github.com/user-attachments/assets/e04ae7e1-81b7-41f6-b8f8-3196d81efb01)
![Screenshot 2024-07-31 223458](https://github.com/user-attachments/assets/303e350d-ff27-4531-8e29-a6ce53120716)
![Screenshot 2024-07-31 223510](https://github.com/user-attachments/assets/6a77d7b7-d170-4882-91f4-aa706cbba46b)

