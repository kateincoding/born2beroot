# Evaluation

## Overview

*  Basic functioning of the virtual machine

A virtual machine, commonly shortened to just VM, A Virtual Machine (VM) is a compute resource that uses software instead of a physical computer to run programs and deploy apps (is no different than any other physical computer). It has a CPU, memory, disks to store your files, and can connect to the internet if needed. While the parts that make up your computer (called hardware) are physical and tangible, VMs are often thought of as virtual computers or software-defined computers within physical servers, existing only as code.

![VM](https://azurecomcdn.azureedge.net/cvt-c6423f74796365dad64d76835f10a79b10d64b0ec5f06b8061d1a854a4cd1ed1/images/page/overview/what-is-a-virtual-machine/overview-img.png)

* How does a virtual machine work?
Virtualization is the process of creating a software-based, or "virtual" version of a computer
 A virtual machine is a computer file, typically called an image, that behaves like an actual computer. It can run in a window as a separate computing environment, often to run a different operating system—or even to function as the user's entire computer experience—as is common on many people's work computers. The virtual machine is partitioned from the rest of the system, meaning that the software inside a VM can't interfere with the host computer's primary operating system.

* Choice of operating system?
Debian

The families and representative lINUX distributions we are using are: 

Red Hat Family Systems (including CentOS and Fedora)
SUSE Family Systems (including openSUSE)
Debian Family Systems (including Ubuntu and Linux Mint).

![Linux distributions](https://courses.edx.org/assets/courseware/v1/1d8c97abd237dcd44a5fe5464f6521ac/asset-v1:LinuxFoundationX+LFS101x+1T2020+type@asset+block/chapter01_The_Linux_Kernel_Distribution_Families_and_Individual_Distributions.png)

** The Debian Family
 Debian is a pure open source community project (not owned by any corporation) and has a strong focus on stability.![debian family](https://courses.edx.org/assets/courseware/v1/223d3c300d6cdd86ae66e8c2b9faa265/asset-v1:LinuxFoundationX+LFS101x+1T2020+type@asset+block/chapter01_screen20.jpg)

Some key facts about the Debian family are listed below:

The Debian family is upstream for Ubuntu, and Ubuntu is upstream for Linux Mint and others.
Kernel version 4.15 is used in Ubuntu 18.04 LTS.
It uses the DPKG-based APT package manager (using apt, apt-get, apt-cache, etc. which we cover in detail later) to install, update, and remove packages in the system.
Ubuntu has been widely used for cloud deployments.
While Ubuntu is built on top of Debian and is GNOME-based under the hood, it differs visually from the interface on standard Debian, as well as other distributions.


