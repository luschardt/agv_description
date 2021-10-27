# agv_description

Pacote para simulação projeto AGV. 

- **Criar uma workspace** 
```sh
$ mkdir -p catkin_ws/src
$ cd catkin_ws/src
```
- **Clone do repositório**
```sh
$ git clone https://github.com/luschardt/agv_description.git
```
- **Compilar workspace e utilizar o pacote de execução**
```sh
$ cd ..
$ catkin_make
$ source devel/setup.bash
$ roslaunch agv_description gazebo.launch  
```
