# cartpole-openai-ros-examples
Training script implementations for Cart Pole

code from [openai-ros-examples](https://bitbucket.org/theconstructcore/openai_examples_projects/src/master/)
* Modified keras imports in cartpole3D_mbalunovic_algorithm_with_rosparams.py 

# dependencies:
* ROS Kinetic on Ubuntu 16.04
* OpenAI Gym 0.16 (last version to support Python 2.7)
* Tensorflow 2.1.0 (last version to support Python 2.7)

# to run:
* assuming cartpole-openai-ros-sim package is in workspace
* catkin_make
* source devel/setup.bash
* roslaunch cartpole_openai_examples main.launch
