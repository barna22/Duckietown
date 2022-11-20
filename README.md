# duckduck
Duckietown reinforcement learning project

Team name: Syntax Terror

Members:
- Istenes Dóra PQ08W1
- Kenesei Benjámin MS725L
- Suciu Barnabás ASOG9J

The aim of this project is to train a reinforcement learning agent in a simulated autonomous driving environment. The agent is referred to as a "duckiebot", and it is trained using reinforcement learning in the simulator, then it can be transferred to a real model vehicle in the physical test environment.

The repository contains the simulation environment, and the scripts and configuration files necessary for the trainig.

## Setup and simulation

After installing the packages specified in the requirements file, the simulation environment can be started with the following command:

```python manual_control.py --env-name Duckietown-udem1-v0```

The running application looks like this with the default config:
![image](https://user-images.githubusercontent.com/40472516/198076371-1fcbf3bd-faa4-41a7-9832-6be3accf1709.png)

## Training

After fixing several errors related to outdated code, and moving train_reinforcement.py and enjoy_reinforcement.py scripts from /learning/reinforcement/pytorch to /learning, we can run the training with the following command:

```python3 train_reinforcement.py```

