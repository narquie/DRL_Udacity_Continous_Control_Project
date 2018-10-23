# DRL_Udacity_Continous_Control_Project
The environment is a 3D space where an AI attempts to apply torque to a double jointed arm to be positioned in a target location. Each second in the location is +.1 reward.

The state space is of length 33 and the action space is of length 4. The state space details the visual aspect of the 3D space in terms of position and rotation, as well as the velocity of the joints. The actions are a vector of length 4 which is the torque applied to either of the two joints.

An agent with the average score of 30 over the 100 latest epsiodes has been considered to solve the environment!

To run the project in windows, pytorch and unityagents packages must be installed. Pytorch's instructions for downloading are here: https://pytorch.org/ and unityagents instructions for downloading are here: in command line (after installing python 3), use "pip install unityagents". You will also need to unzip the folder for the Research.exe as the folder is named at the moment.

The project will be ready to run after all dependencies are met! Training an AI can and probably will use a lot of processing power, so do not be surprised if your computer suddenly is performing more than usual.

This project was heavily based on the source code from the Udacity program. I have made updates to how the agent is updated and the architecture of the neural networks.
