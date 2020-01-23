# Cartpole-v0-game-using-Reinforcement-learning
Gym is a toolkit for developing and comparing reinforcement learning algorithms. It makes no assumptions about the structure of your 
agent, and is compatible with any numerical computation library. We are implementing it in the project to run an instance of the 
Cartpole-v0 environment for 1000 timesteps, rendering the environment at each step

PROBLEM  STATEMENT:
Training an agent to play Cartpole game using Reinforcement learning.

MAIN THEME OF THE GAME:
A pole is attached by an un-actuated joint to a cart,which moves along a frictionless track.The system is controlled by applying a 
force of +1 or -1 to the cart.The pendulum starts upright,and the goal is to prevent it from falling over.A reward of +1 is provided 
for every timestep that the pole remains upright.The episode ends when the pole is more than 15 degrees from vertical,or the cart moves 
more than 2.4 unts from the center.

OBSERVATIONS:
The environment’s step function returns exactly what we need. In fact, step returns four values. These are:

●	observation (object): an environment-specific object representing your observation of the environment. For example, pixel data froma 
camera, joint angles and joint velocities of a robot, or the board state in a board game.

●	reward (float): amount of reward achieved by the previous action. The scale varies between environments, but the goal is always to 
increase your total reward.

●	done (boolean): whether it’s time to reset the environment again. Most (but not all) tasks are divided up into well-defined episodes, 
and done being True indicates the episode has terminated. (For example, perhaps the pole tipped too far, or you lost your last life.)

●	info (dict): diagnostic information useful for debugging. It can sometimes be useful for learning (for example, it might contain the
raw probabilities behind the environment’s last state change). However, official evaluations of your agent are not allowed to use this 
for learning.

WORKING:
This is just an implementation of the classic “agent-environment loop”. In each step, the agent chooses an action, and the environment 
returns an observation and a reward.
 
The process gets started by calling reset(), which returns an initial observation Training an agent to play Cartpole game using 
Reinforcement learning.
 
SOFTWARE AND HARDWARE REQUIREMENTS:
Jupyter Notebook

Tensorflow

Keras

Open AI Gym


 
 
 

