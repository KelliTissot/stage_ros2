
### Requirement  
```bash
git clone https://github.com/rtv/Stage.git ~/Stage# stage lib
cd ~/Stage
mkdir build && cd build
cmake ..
make && sudo make install
```
  
### build
```bash
cd ~your_ws/src/
git clone https://github.com/n0nzzz/stage_ros2.git # stage_ros2 wrapper
cd ~ros2_ws/
colcon build
```

```bash
git@github.com:tuw-robotics/stage_ros2.git # Clonar este repositório fora do ws apenas para extrair o mapa cave.world
```

### launch
```bash
cd ros2_ws/
. install/setup.bash
```
```
# ros2 run staget_ros stageros (world file Absolute path)
ros2 run stage_ros stageros src/stage_ros2/world/cave.world
```

```
cd ros2_ws/
ros2 run stage_ros targets.py
```
