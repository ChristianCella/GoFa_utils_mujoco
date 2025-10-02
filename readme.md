To export a urdf in ubuntu 22.04 (for example):

```
ros2 run xacro xacro --inorder   -o crb15000_5_95.urdf   /home/kriscell/Projects/mics_ws/src/abb_omnicore_ros2/robot_specific_config/abb_crb15000_support/urdf/crb15000_5_95/crb15000_5_95.xacro   use_fake_hardware:=true   rws_ip:=192.168.125.1   rws_port:=443   configure_via_rws:=false

```