# Safe Reinforcement Learning with Natural Language Constraints
To clone the code:
```
git clone --recurse-submodules https://github.com/princeton-nlp/SRL-NLC.git
```
Next, install submodules within pip.
```
cd SRL-NLC

cd hazard-world-grid
pip install -e .

cd ../hazard-world-robot
pip install -e .

cd ../safety-starter-agents
pip install -e .
```


## HazardWorld

HazardWorld is composed of two environments: HazardWorld-grid and HazardWorld-robot.

### HazardWorld-grid

HazardWorld-grid is a 2D GridWorld environment with partial observability. It is built off of the [gym-minigrid](https://github.com/maximecb/gym-minigrid) environment. 

Raw link to `hazard-world-grid` repo: <https://github.com/michahu/hazard-world-grid>.
### HazardWorld-robot

Before running HazardWorld-robot, you must first install MuJoCo 2.0, available from <https://www.roboti.us/download.html>. MuJoCo is now free. 
1. Unpack the mujoco binary downloaded from the link above inside the directory `~/.mujoco`. 
2. Place the your product key `mjkey.txt` inside `~/.mujoco`.
3. Run: `export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/michahu/.mujoco/mujoco200/bin`

MuJoCo 2.1 is available from <https://mujoco.org/>, but dependencies of `SRL-NLC` have not been updated for MuJoCo 2.1. 

HazardWorld-robot is a 3D MuJoCo environment. It is built off of [safety-gym](https://github.com/openai/safety-gym). 

Raw link to `hazard-world-robot` repo: <https://github.com/michahu/hazard-world-robot>.


## Models for SRL-NLC

Models compatible with both HazardWorld-grid and HazardWorld-robot are in the `safety-starter-agents` folder. This submodule is built off [safety-starter-agents](https://github.com/openai/safety-starter-agents). 

Raw link to `safety-starter-agents` repo: <https://github.com/michahu/safety-starter-agents>.
