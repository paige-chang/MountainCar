# MountainCar

This repository contains my project that solve a classical control problem using SARSA-Lambda reinforcement learning algorithm. 

![Output sample](mountaincar.gif)


The goal of the MountainCar task is to drive up a car to the mountain hill on the right. As the car's engine is not strong enough to scale the mountain in a single pass, the only way for the agent to succeed is to learn how to leverage the gravity, driving back and forth to build up momentum. For any given moment of the car, the agent can choose driving left, driving right, or not using the engine at all. MountainCar-v0 in OpenAI Gym defines the target as getting average reward of -110.0 over 100 consecutive trials. 



