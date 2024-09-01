# gazebo-sim-env
**robotpi**

# Target

## Robot arm with gripper to grip object on table


# Useful Tutorial

1. [Getting Ready to build a ROS robot](https://articulatedrobotics.xyz/category/getting-ready-to-build-a-ros-robot)
1. [moveit\_task\_constructor](https://github.com/moveit/moveit_task_constructor)

# Tips

Q: How to solve ros dependency

```
sudo rosdep init
rosdep update

cd your_workspace_path
rosdep install -r --from-paths . --ignore-src --rosdistro $ROS_DISTRO -y
```
