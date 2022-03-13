# INF581 project: BipedalWalker

In this project, we implement several reinforcement learning algorithms to try to get the best score at the OpenAI Gym's BipedalWalker environment.
Here are some instructions to run them:

### Deep Q-Network (DQN)
Run 'dqn_discrete_walker.ipynb' in a Google Colab environment with GPU enabled.
Weights for the network are provided in 'DQN_weights.dat', jsut change the path for loading / saving weights to skip training (currently the training saves results in Google Drive if you mount it to the notebook).

### Genetic Algorithm
Run the `Genetic.ipynb` notebook with the `genetic.py` file being in the same folder.

### Deep deterministic Policy Gradient (DDPG)
For DDPG with standard replay buffer, run the `DDPG_Standard_Buffer_Replay.ipynb` notebook. Running it on GPU is recommended.
For DDPG with Prioritized Experience Replay, run the `DDPG_Prioritized_Experience_Replay.ipynb` notebook with the `utils.py` file being in the same folder.
The outcome of 2000-episode training can be seen on the video called `DDPG_Video_Best_Parameters.mp4`.

### Proximal Policy Optimization (PPO)
For PPO, run the `PPO.ipynb` notebook.
