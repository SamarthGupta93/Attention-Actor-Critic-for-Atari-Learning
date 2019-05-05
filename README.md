# Attention-Actor-Critic-for-Atari-Learning
Attention Actor Critic for Atari Learning 

This is a Reinforcement Learning based Actor Critic model for Atari Games Learning. The repository contains three different architectures. 

### Attention Model
Uses dot product attention mechanism as explained in the paper "Attention is all you need" in an Actor Critic network to predict future actions. Requires one frame as state input

![alt text](https://github.com/SamarthGupta93/Attention-Actor-Critic-for-Atari-Learning/blob/master/attention_model.PNG)

#### Attention Visualization
![alt text](https://github.com/SamarthGupta93/Attention-Actor-Critic-for-Atari-Learning/blob/master/brko_attention.PNG)

### Recurrent Model
Uses a Gated Recurrent Unit to understand temporal dependencies in order to predict future actions. Requires one frame as state input.

![alt text](https://github.com/SamarthGupta93/Attention-Actor-Critic-for-Atari-Learning/blob/master/gru_model.PNG)

### Convolutional Model
conv-a3c.py uses convolutional network to predict optimal actions. It uses four frames as state input.

![alt text](https://github.com/SamarthGupta93/Attention-Actor-Critic-for-Atari-Learning/blob/master/Conv_model.PNG)
