# GeminiFlight
![GeminiFlight Logo](Logo.png)

## Open Source Drone Flight Stack Optimised for Low Cost and High Customisability
GeminiFlight consists of a flight stabilisation unit (the firmware) paired with an autopilot unit (the host). The goal is to have a simple configurable firmware, with complex high level general purpose software control. This distinction helps offload computationally expensive tasks to a microprocessor that's better suited to handle them and only keeping hard real-time tasks on the microcontroller. This reduces both costs and complexity. It also also opens up the platform for use in both manual recreational drones and autonomous enterprise drones. This dual-brain architecture was greatly inspired by the harmonious duality of the [Neocortex](https://en.wikipedia.org/wiki/Neocortex) and the [Limbic System](https://en.wikipedia.org/wiki/Limbic_system) in the human brain and is also where GeminiFlight gets it's name from.

The core belief is that simplicity is the ultimate sophestication. That performance does not come from the speed of the programming language itself but from being able to develop and iterate on more efficient algorithms and architectures. GeminiFlight will continue using Arduino and Node-Red in it's stack in the forseeable future. We will not accept any PRs that prioritize performance at the cost of readability, maintainability or hackability.

## How to get started?

### Step 1
[Join Our Discord Server](https://discord.gg/HdWe3RSFJ6)

### Step 2
Flash Raspberry Pi OS Lite Legacy 32-Bit on the Raspberry Pi

### Step 3
Install Git
```
sudo apt update && sudo apt install git
```
### Step 4
GeminiFlight uses a git submodule structure to organise it's code.
```
git clone --recurse-submodules https://github.com/Udan-Khatola/GeminiFlight.git 
```
### Step 5
Install Node-Red and NodeJS
```
bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)
```
### Step 6
Open the folder in [VSCode](https://code.visualstudio.com/) & install any extensions you get prompted for.
Open individual submodule folders for further setup instructions .
