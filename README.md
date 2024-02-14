# ROS from Source

## Build ros from source without using a PPA

```bash
mkdir build
cd build
../git_clone.sh
sudo ../dependencies.sh
../build.sh
```

## Source setup script and run roscore

```bash
source .../ros_from_src/build/catkin_ws/devel/setup.bash
roscore
```
