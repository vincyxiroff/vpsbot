# vpsbot
Allows you to create &amp; admin LinuxContainers (LXC) Using Discord 

# Requirements:
- Python3 (apt pkg)
- wondersharper (apt pkg)
- screenfetch (apt pkg)
- git (apt pkg)
- snapd (apt pkg)
- lxd (snapd binary)
- discord (python lib)
- psutil (python lib)

# Server Requirements:
- Any 1 Gb KVM Server will work (Testing Env)
- Any 8 Gb KVM Server will also work (Production Env)

# Tested Devices:
- Raspberry Pi 4 (4 GB Model)
- Old 2Gb Dell Laptop
- 4Gb 1Vcore KVM Server

# Installation!
First make sure to modify *main.py* to your needs then do
- **apt install screenfetch git wondersharper snapd -y && snapd install lxd && lxd init**
- **pip install discord psutil**
- **git clone https://github.com/dxomg/vpsbot**
- **cd lxcbot**
- **python3 main.py**
