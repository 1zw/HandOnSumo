# TRAFFIC_LIGHT_DQN

@Author: 1zw  
@Email: 2200120323@stu.hit.edu.cn  
@Date: 2023-04-27 00:23:00

## Introduction
This is a project for myself to learn how to train a DQN model to control a traffic light.  
And this project has reference to some other projects, such as [sumo-rl](https://github.com/LucasAlegre/sumo-rl), you can check it out if you are interested in this project.

## Requirements
- python 3.10
- torch
- absl
- traci
- sumolib(if you have sumo installed)

## How to use
- run `python main.py` to train a model
- run to evaluate the model 
  ```bash
  python -u "d:\eternal_sumo\HandOnSumo\demo\traffic_light_dqn\main.py" --use_gui --num_episodes=1 --network_file=weights/weights_20221020.pth --mode=eval
  ```
## Need to do
- [ ] use other RL algorithms to train the model
- [ ] give visual feedback 