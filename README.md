# RL-Game-Playing-Agent
DDQN based self learning game playing agent for Mario Bros V = 0
# Requirements
gym  
torchrl  
tensordict
# Working
Import enviroment of the game  
Preprocess the frames of the enviroment by converting frames into grayscale and resizing  
Build the agent  
Checks previous buffer replay  
Agent runs an episode and stores the results in buffer replay  
