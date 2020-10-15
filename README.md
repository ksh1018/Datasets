# Datasets
This datasets were acquired in a corridor style building and a narrow dwelling space as shown in Figure 1 and Figure 2.

<div style="text-align:center"><img src="Indoor_environment_1.png"  width="360" height="240"></div>
Figure 1. Indooor environment 1


<div style="text-align:center"><img src="Indoor_environment_2.png"  width="360" height="240"></div>
Figure 2. Indooor environment 2



This datasets consist of RGB images, thermal IR images, 2D LiDAR data, IMU data and UWB data as shown in Figure 3.

<div style="text-align:center"><img src="data_structure.png" width="360" height="240"></div>
Figure 3. Data structure 



All data are provided in a compressed 'zip' format and stored in a folder with the date and time the data was collected.



## Data Format
- RGB images
Width: 640, Height: 480 8UC3

- Thermal IR images
Width: 160, Height: 120 16UC1

- 2D LiDAR data
Fov: 360, resolution: 0.3
(count, Vector<(quality, angle, distance)>)

- IMU data
(time, check, accel x, accel y, accel z, gyro x, gyro y, gyro z, NWU w, NWU x, NWU y, NUW z)

- UWB data
(try,data)



## Dataset Download



