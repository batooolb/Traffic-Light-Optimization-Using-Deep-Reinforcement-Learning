# Traffic-Light-Optimization-Using-Deep-Reinforcement-Learning

This manual aims to assist individuals or departments in charge of traffic and road management, particularly those in charge of traffic signals. To get the most out of this system, users should have a clear understanding of SUMO (Simulation of Urban Mobility), as well as the ability to produce SUMO files such as network (net) and route files. 

Please follow the steps below to be properly led through the installation and setup procedure.

**Step 1**: Install SUMO and Dependencies
1. Install an Ubuntu terminal on your device.
2. Open the Ubuntu terminal.
3. Run the following command to add the SUMO repository:
**sudo add-apt-repository ppa:sumo/stable**
4. Run the following command to update the package list:
sudo apt-get update
5. Run the following command to install SUMO, SUMO code, and SUMO documentation:
**sudo apt-get install sumo sumo-tools sumo-doc**

**Step 2:** Set SUMO HOME Variable
1. Run the following command in the terminal to add the SUMO HOME variable
to your /.bashrc file:
**echo ‘export SUMO HOME=“/usr/share/sumo”’>> ∼/.bashrc**
2. Run the following command to activate the modifications made to ∼/.bashrc:
**source ∼/.bashrc**

**Step 3:** Install Python Dependencies
1. Run the following command to install the additional Python dependencies required for our system:
**pip install numpy pandas matplotlib scipy tensorboard**
2. Torch, a machine learning library, must also be installed. Please see the official PyTorch website for installation instructions.

**Step 4:** Install Stable Baselines3
1. Run the following command to install Stable Baselines3 which includes reinforcement learning algorithms:
**pip install stable-baselines3[extra]**
