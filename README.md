# Project: Map My World

<img src=2Dmap.png width=800 />
<img src=3Dmap.png width=800 />


rtabmap.db file is [here](https://drive.google.com/file/d/1ckwr4LpbzcU4ebOojkYGsW2GrYUrZ4KL/view?usp=sharing).

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
$ roslaunch teleop_twist_keyboard teleop.launch
```
