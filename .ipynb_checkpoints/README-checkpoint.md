# Reinforcement-Learning-Cartpole
Using pytorch to train a Deep Learning Q Learning agent to play CartPole. 

# Cartpole
----
The aim of cartpole is to maintain the pole in an upright position. 
The agent can choose to move the cart to the left or the right. 

![Alt Text](https://pytorch.org/tutorials/_images/cartpole.gif)

As stated on the [pytorch tutorials page](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html)
> As the agent observes the current state of the environment and chooses an action, the environment transitions to a new state, and also returns a reward that indicates the consequences of the action. In this task, rewards are +1 for every incremental timestep and the environment terminates if the pole falls over too far or the cart moves more then 2.4 units away from center. This means better performing scenarios will run for longer duration, accumulating larger return.