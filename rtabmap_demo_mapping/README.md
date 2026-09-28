# rtabmap_demo_mapping

RTAB-Map's official ROS2 demo bag, the one `rtabmap_demos/launch/robot_mapping_demo.launch.py`
([introlab/rtabmap_ros](https://github.com/introlab/rtabmap_ros), `ros2` branch) links to:
a ROS2 sqlite3 bag with RGB-D (compressed), laser scan, odometry and `/tf`. It has no groundtruth.

Download it into this folder:

```
cd rtabmap_demo_mapping
curl -L -o demo_mapping.zip "https://drive.usercontent.google.com/download?id=1v9qJ2U7GlYhqBJr7OQHWbDSCfgiVaLWb&export=download&confirm=t"
unzip demo_mapping.zip && rm demo_mapping.zip
```

The folder then holds `demo_mapping_bag/metadata.yaml` and `demo_mapping_bag/demo_mapping.db3`
(sha256 `b233777634dea8207677d7a76d76718b43bc7043f03d061f6c332f12a9e07be8`).
