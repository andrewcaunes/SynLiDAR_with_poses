# [SynLiDAR](https://github.com/xiaoaoran/SynLiDAR) fork with added scan poses computed using [Kiss-ICP](https://github.com/PRBonn/kiss-icp).

The original SynLiDAR was shipped without any LiDAR poses, which makes it impossible to apply any time or projection based method. The [synlidar_poses](synlidar_poses) folder contains the poses in KITTI format as computed using state-of-the-art visual odometry method Kiss-ICP.

Just copy the [synlidar_poses/sequences](synlidar_poses/sequences) folder into you SynLidar dataset folder.
