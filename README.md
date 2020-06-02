# Pong-DRL
We will learn to implement and train a policy to play atari-pong, using only the pixels as input. We will use convolutional neural nets, multiprocessing, and pytorch to implement and train our policy. Let's get started!

![](images/Annotation%202020-06-01%20013241.png)

![](images/Annotation%202020-06-01%20013302.png)
open pong-Reinforc.ipy 

Pre-requsits :
torch : installation source (https://pytorch.org/)
numpy : pip install numpy
JSAnimation : included in the script
gym : pip install gym
matplotlib : pip install

!!!!!!!!!!!!!!!!!
 WARNING: make sure to turn on GPU, which also enables multicore processing. It may take up to 45 minutes even with GPU enabled, otherwise it will take much longer.

![](images/Annotation%202020-06-01%20013318.png)

#---------UPDATE PONG PPO-------------#
In Pong PPO we use a clipper to enhance the performence
