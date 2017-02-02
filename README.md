# MBIZRC_Challenge2

Install all dependencies, then run:

`roslaunch summit_xl_sim_bringup summit_xl_complete.launch` for simulation (in summit_xl_sim/summit_xl_gazebo/worlds/summit_xl.world, make sure the "panel" file uri matches your home directory)

and

`rosrun teleop_twist_keyboard teleop_twist_keyboard.py` for manual keyboard control

packages that need to be installed besides ros-desktop 
include: 

ros-indigo-mavros-msgs

ros-indigo-robot-localization

ros-indigo-robotnik-msgs

ros-indigo-robotnik-sensors 

ros-indigo-gazebo-ros-control

ros-indigo-joint-state-controller

add ros-indigo-move-base
**don't use *indigo* if not using ubuntu 14.04 LTS 

https://github.com/tu-darmstadt-ros-pkg/hector_laserscan_to_pointcloud
