# Kidnapped-Vehicle
Using 2D Particle filter to localize the vehicle. To the particle filter algorithm we provide, map of the location, initial location estimate, and sensor and control data.

## Setting up the project workspace
### setting up the term2 simulator

This project uses udacity term2 simulator which can be downloded from [here](https://github.com/udacity/self-driving-car-sim/releases)

Extract the contents 

from the directory: 

`chmod +x ./term2_sim.x86_64`

### setting up and installing uWebSocketIO (ubuntu)

installing zlib

`sudo apt-get install zlib1g-dev`

installing the make and cmake

`sudo apt-get install build-essential cmake`

installing uWebSocketIO

`chmod +x install-ubuntu.sh`

`./install-ubuntu.sh`

### Building the projecting and running

From the top directory of the project Car

`./clean.sh`

`./build.sh`

`./run.sh`

(If runnning for first time use `chmod +x file.sh` to grant access to .sh files)

After running `./run.sh` we can see

`Listening to port 4567` message in the terminal

### Starting udacity simulator

in a new terminal navigate to the directory where we have the simulator extracted and run,

`./term2_sim.x86_64`

Choose the resolution of the simulator window and you should be seeing the following window

Simulator:

![](https://github.com/sbperceptron/Kidnapped-Vehicle/blob/master/Simulator.png)

Go to Kidnapped Vehicle page of the simulator and hit select,

![](https://github.com/sbperceptron/Kidnapped-Vehicle/blob/master/simulator_kidnapped_vehicle.png)
