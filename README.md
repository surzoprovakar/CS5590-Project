Installation
------------

To run the project, we need to install Python3, pip3, simpy and pyCryptodome.
SimPy requires Python >= 3.6, both CPython and PyPy3 are known to work.
The following installation instructions are for Linux OS.

## Install Python3.10
- sudo apt update && sudo apt upgrade -y
- sudo apt install software-properties-common -y
- sudo add-apt-repository ppa:deadsnakes/ppa
- sudo apt install python3.10

## Install Pip3
sudo apt-get -y install python3-pip

## Install Simpy
pip3  install -U simpy

## Install PyCryptodome
pip3 install -U PyCryptodome 

## Run the Project in Linux [GO inside the code directory]
make

## Clean the Project in Linux
make clean