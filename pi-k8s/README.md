# pi-k8s

Let's try k8s on Raspberry Pi...

Currently this configuration just does all the package installation needed to get things going.

## Installation

* Install Ubuntu 20.04 64 bit onto an SD card (https://ubuntu.com/download/raspberry-pi)
* Copy the files in this directory to the root directory of that SD card
* Safely eject the SD card and insert it into your Raspberry Pi 3 or 4
* Power up and go

If you're not me running on my network, ensure you at least make the following changes:
* Change the SSH key allowed to log in to the system in `user-data`
* Change the IP address of the system in `network-config`
