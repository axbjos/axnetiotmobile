# IoT Lab: Node-Red/MQTT/MongoDB

## Single Virtual Machine Based Installation for Laptops and Desktops

### Description

This repository contains instructions, configuration, and code for the implementation of three common platforms used for constructing an event-based architecture for exploring IoT concepts.

### Base Materials

* Any modern laptop or desktop with the capability to run a Virtual Machine Hypervisor such as VirtualBox
* The Oracle VirtualBox hypervisor (free) from www.virtualbox.org
* Ubuntu Server v20.04 (or 18.04) from https://releases.ubuntu.com/20.04/
* For a full experience a Raspberry Pi is also needed.  
* For an even more full experience an Arduino Uno (or other Arduino - a Pro Micro or Mega would work as well)
* M1-based Macs are supported as well.  The Parallels Technical Preview Hypervisor is the only hypervisor currently available for M1-based Macs: https://www.parallels.com/blogs/parallels-desktop-apple-silicon-mac/  The technical preview is currently free. The ARM processor version of Ubuntu 20 will be needed instead.

### Part 1 - Create the Virtual Machine

This guide creates the IoT Lab by implementing all services and platforms on a single Virtual Machine.

The author is a proponent of using Virtual Machines for running the platforms discussed in this guide such as Node Red, MQTT, and MongoDB. All of these platforms could be installed directly on a Windows, Mac, or Linux PC.  However by installing them on a Linux Server running as a Virtual Machine, the IoT Lab can be more easily controlled (shutdown,started, etc), there are more options for controlling networking and security, and the host machine is not "contaminated" by sprawling software platforms that the user may not want causing potential issues on their primary workstation.


