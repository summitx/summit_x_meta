# ROS metapackage for summit_x robot simulation

## Melodic
### Clone repo and submodules

    $ cd /path/to/catkin/ws
    $ mkdir src
    $ cd src
    $ git clone --recurse-submodules git@github.com:summitx/summit_x_meta.git

### Install dependencies

    $ sudo apt install ros-melodic-costmap-2d ros-melodic-robot-localization ros-melodic-mavros-msgs ros-melodic-gmapping ros-melodic-map-server ros-melodic-amcl ros-melodic-teb-local-planner ros-melodic-move-base ros-melodic-velocity-controllers ros-melodic-twist-mux

### Build

    $ cd /path/to/catkin_ws
    $ catkin_make
