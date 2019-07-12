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
