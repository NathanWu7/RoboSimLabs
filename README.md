# RoboSimLabs
Integrate simulation environments such as Isaac Gym, Isaac Lab, and Genesis, as well as a unified robotic simulation framework with interfaces for reinforcement learning, imitation learning, and large language models (LLMs).


## 1. Preparations

It is recommended to use the Ubuntu system (>=20.04) with the latest NVIDIA dependencies installed, including the graphics driver, CUDA, and cuDNN.


And it is recommended to use a Conda(or miniconda) virtual environment for the best user experience.


```bash
# Activate conda environment
conda activate yourenv
```
**Please set up isolated simulation environments for different simulators.**



### 1.1 Isaac series

Older version: Isaacgym (Python<=3.8 and please check your CUDA version and other dependencies.)

- [Isaac Gym](https://developer.nvidia.com/isaac-gym)

Latest: Isaac Sim and IsaacLab (Recomended). 

- [Isaac Sim](https://docs.omniverse.nvidia.com/isaacsim/latest/index.html)
- [Isaac Lab](https://isaac-sim.github.io/IsaacLab/)

For locomotion tasks:



For manipulation tasks:
```bash
cd manipulation
git clone https://github.com/NathanWu7/isaacLab.manipulation.git
cd isaacLab.manipulation
python -m pip install -e .
```

### 1.2 Genesis

- [Genesis](https://github.com/Genesis-Embodied-AI/Genesis)


### 1.3 Maniskill(TODO)







