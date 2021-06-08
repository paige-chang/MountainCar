# MountainCar

This repository contains implementations of algorithms that solve a reinforcement learning problem - mountain car. The environment is provided by the OpenAI Gym (MountainCar-v0). 

![Output sample](mountaincar.gif)


The goal of the task is to drive up the mountain on the right. Since the car's engine is not strong enough to scale the mountain in a single pass, the only way to succeed is to learn to leverage the gravity, and drive back and forth to build up momentum. For any given state (position and velocity) of the car, the agent is given the choice of driving left, driving right, or not using the engine at all. MountainCar-v0 defines "solving" as getting average reward of -110.0 over 100 consecutive trials.  The agent receives a negative reward at every step when the goal is not reached. 

I implemented SARSALamda with function approximation that solved the problem within 300 episodes

