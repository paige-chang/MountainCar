# MountainCar

![Output sample](mountaincar.gif)


The goal of the MountainCar task is to drive up a car to the mountain hill on the right. As the car's engine is not strong enough to scale the mountain in a single pass, the only way for the agent to succeed is to learn how to leverage the gravity, driving back and forth to build up momentum. The reward is very sparse in the MountainCar task. The car has to move more than 50 times before it receives 1 reward. I implemented SARSA-Lambda reinforcement learning that optimized a sequence of movements to maximize momentum. The algorithm solved the task within 300 episodes.



