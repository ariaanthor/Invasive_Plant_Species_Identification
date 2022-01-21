# Invasive_Plant_Species_Identification
Used LiDAR Odometry and Mapping (LOAM) to create a 3D point cloud map which can be used to identify invasive plant species.
## What is LOAM
Mapping with lidars is common as lidars can provide high frequency range measurements where errors are relatively constant irrespective of the distances measured. If the lidar is stationary, then generating the point cloud is simple. However, if the lidar itself is moving, then accurate mapping requires knowledge of the lidar's pose during continuous laser ranging.
## Why LOAM
One common way to solve the problem of pose estimation is to use independent position estimation (usually GPS/INS) to register the laser points into a fixed coordinate system. This works well, but it fails if connection to the GPS/INS is lost. Another set of methods use odometry measurements such as from wheel encoders or visual odometry systems to register the points.
