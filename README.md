# Reinforcement Learning

# Libraries

- [gym-super-mario-bros](https://pypi.org/project/gym-super-mario-bros/)
- [nes_py](https://pypi.org/project/nes-py/)
- [stable_baseline](https://stable-baselines3.readthedocs.io/en/master/index.html)

# Enviroments


# DQN - Vanilla

| Hyperparameters | Values    | Other Parameters | Values |
| ------------ | ------------ | ------------ | ------------ |
|  learning_rate  |  0.00004 | Checkpoints | 20  |
|  batch_size | 250  | Iteraations | 2M   |
|  learning_start | 5000  |  Train Length | 24h  |
| buffer_size |  5000 | 


 
| Rewards | Distance    | Gif 10th Checkpoint    | 
| ------------ | ------------ | ------------ |
| <img src="/1_DQN_VAN/rewards.png" width="300" height="221">  |  <img src="/1_DQN_VAN/max_distance.png" width="300" height="221">  | <img src="/1_DQN_VAN/10_31.gif" width="350" height="196">  |


[summary]

# DQN - Only Right

| Hyperparameters | Values    | Other Parameters | Values |
| ------------ | ------------ | ------------ | ------------ |
|  learning_rate  |  0.00004 | Checkpoints | 20  |
|  batch_size | 250  | Iteraations | 2M   |
|  learning_start | 5000  |  Train Length | 24h  |
| buffer_size |  5000 | 


| Rewards | Distance    | Gif 16th Checkpoint    | 
| ------------ | ------------ | ------------ |
| <img src="/2_DQN_OR/rewards.png" width="300" height="221">  |  <img src="/2_DQN_OR/max_distance.png" width="300" height="221">  | <img src="/2_DQN_OR/16_32.gif" width="350" height="196">  |


[summary]

# PPO Vanilla

| Hyperparameters | Values    | Other Parameters | Values |
| ------------ | ------------ | ------------ | ------------ |
|  learning_rate  |  0.000001 | Checkpoints | 35  |
|  n_steps | 512  | Iterations | 35M   |
|  batch_size | 64 |  Train Length | 12h  |


| Rewards | Distance    | Gif 28th Checkpoint    | 
| ------------ | ------------ | ------------ |
| <img src="/3_PPO_VAN/rewards.png" width="300" height="221">  |  <img src="/3_PPO_VAN/max_distance.png" width="300" height="221">  | <img src="/3_PPO_VAN/30_28.gif" width="350" height="196">  |

[summary]

# PPO Custom Classifier

| Hyperparameters | Values    | Other Parameters | Values |
| ------------ | ------------ | ------------ | ------------ |
|  learning_rate  |  0.000001 | Checkpoints | 35  |
|  n_steps | 4096  | Iterations | 35M   |
|  batch_size | 64 |  Train Length | 12h  |


| Rewards | Distance    | Gif 30th Checkpoint    | 
| ------------ | ------------ | ------------ |
| <img src="/4_PPO_CL2/rewards.png" width="300" height="221">  |  <img src="/4_PPO_CL2/max_distance.png" width="300" height="221">  | <img src="/4_PPO_CL2/30_25.gif" width="350" height="196">  |

[summary]