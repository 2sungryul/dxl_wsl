# dxl_wsl

$ cd ~/ros2_ws/src

$ git clone https://github.com/2sungryul/dxl_wsl.git

$ cd ~/ros2_ws

$ colcon build --symlink-install --packages-select dxl_wsl

$ source install/local_setup.bash

$ ros2 run dxl_wsl pub
