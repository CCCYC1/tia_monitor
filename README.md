![d1](https://user-images.githubusercontent.com/95714572/234139080-18f8e435-d6da-4bbf-9c8c-5f30205690c0.png) https://discord.com/channels/638338779505229824/1077540791095939082/1095346695501525032

Inspired by this announcement, I created a tool to monitor CPU usage, Memory usage, Disk usage, Remaining Disk Space, and data folder size while the node is running.

# Tia_Monitor

This tool monitors the CPU Usage, Memory Usage, Disk Usage, size of the `.celestia-light-blockspacerace-0/data` folder, and remaining disk space on a Linux system running a Celestia Light Node.

## Prerequisites

- Python 3
- psutil library

## Installation

1. Open up another terminal window.
And install Python 3 if you haven't already:
```
sudo apt install python3 python3-pip
```
2. Install the `psutil` library using pip:
```
pip3 install psutil
```
3. Clone the repository:
```
git clone https://github.com/CCCYC1/tia_monitor.git
```
4. Change to the `tia_monitor` directory:
```
cd tia_monitor
```
## Usage
Run the script using the following command:
```
python3 tia_monitor.py
```
This will execute the script, and you should see the CPU usage, Memory usage, Disk usage, Remaining Disk Space and the size of the .celestia-light-blockspacerace-0/data folder being printed every 5 seconds.

![c1](https://user-images.githubusercontent.com/95714572/234147543-3f4b8a59-2b0c-4b34-99fc-891407bcde5b.png)

## This Github repository has already been submitted to Celestia Blockspace Race(Bonus Task)
![c2](https://user-images.githubusercontent.com/95714572/234148589-bcbe7a4f-956f-4df2-8096-680c424576f1.png)
