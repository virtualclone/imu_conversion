# imu_conversion
From NED (the imu on Pixhawk) to ENU
## Running the node
These instructions will let the imu data which is in NED convert to ENU.
```
rosrun imu_conversion NEDtoENU
```
To get the data in ENU
```
rostopic echo /imu/ENU
