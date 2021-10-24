# SRL-NLC
Safe Reinforcement Learning with Natural Language Constraints. To clone the code:
```
git clone --recurse-submodules https://github.com/princeton-nlp/SRL-NLC.git
```


## HazardWorld

HazardWorld is composed of two environments: HazardWorld-grid and HazardWorld-robot.

### HazardWorld-grid

HazardWorld-grid is a 2D GridWorld environment with partial observability. It is built off of the [gym-minigrid](https://github.com/maximecb/gym-minigrid) environment. 

Raw link to `hazard-world-grid` repo: <https://github.com/michahu/hazard-world-grid>.
### HazardWorld-robot

Before running HazardWorld-robot, you must first install MuJoCo, available from <https://mujoco.org/>.

HazardWorld-robot is a 3D MuJoCo environment. It is built off of [safety-gym](https://github.com/openai/safety-gym). 

Raw link to `hazard-world-robot repo`: <https://github.com/michahu/hazard-world-robot>.


## Models for SRL-NLC

Models compatible with both HazardWorld-grid and HazardWorld-robot are in the `safety-starter-agents` folder. This submodule is built off [safety-starter-agents](https://github.com/openai/safety-starter-agents). 

Raw link to `safety-starter-agents`: <https://github.com/michahu/safety-starter-agents>.
