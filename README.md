# dxl_wsl

ros2 dxl test program on WSL2-ubuntu 20.04

# run dxl publisher on WSL2-Ubuntu 20.04

$ cd ~/ros2_ws/src

$ git clone https://github.com/2sungryul/dxl_wsl.git

$ cd ~/ros2_ws

$ colcon build --symlink-install --packages-select dxl_wsl

$ source install/local_setup.bash

$ ros2 run dxl_wsl pub
