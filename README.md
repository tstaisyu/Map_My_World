# Project: Map My World

<img src=2Dmap.png width=800 />
<img src=3Dmap.png width=800 />


rtabmap.db file is [here](https://1drv.ms/u/s!AmeLVFYQNkfqxSstSerZlwgd3PJm?e=Q4igg3).

## To start a simulation

```sh
$ mkdir catkin_ws && cd catkin_ws
$ git clone --recursive https://github.com/tstaisyu/Map_My_World.git src
$ catkin_make
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```

## To start AMCL (on another terminal)

```sh
$ source devel/setup.bash
$ roslaunch localization mapping.launch
```
## To start teleop (on another terminal)

```sh
$ source devel/setup.bash
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```
