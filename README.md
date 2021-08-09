# born2beroot
This document is a System Administration related exercise.

![imagen](https://upload.wikimedia.org/wikipedia/commons/7/78/Debian_logo_redeploiement.png)

There are three major distribution families within Linux: Red Hat, SUSE and Debian.

## Debian
Some key facts about the Debian family are listed below:

* The Debian family is upstream for Ubuntu, and Ubuntu is upstream for Linux Mint and others.
* Kernel version 4.15 is used in Ubuntu 18.04 LTS.
* It uses the DPKG-based APT package manager (using apt, apt-get, apt-cache, etc. which we cover in detail later) to install, update, and remove packages in the system.
Ubuntu has been widely used for cloud deployments.
* While Ubuntu is built on top of Debian and is GNOME-based under the hood, it differs visually from the interface on standard Debian, as well as other distributions.

## Hostname and User

Hostname: <user42>
User: <user>

### How to check

```
cd /home
```

![imagen](https://cdn.guru99.com/images/ls-al(2).png)

## Sudo configuration
Users can execute commands with super-user or root priviligies in a number of different ways.
In this article, we will discuss how to correctly and surely obtain root priviliges with a special focus on editing the etc/sudo file

### Sudo
```
sudo visudo -f /etc/sudoers.d/student
```

### How to see the sudoers in linux
```
cut -d: -f1 /etc/password
```

### PAM password securitu

Install this library
```
sudo apt install libpam-pwquality
```

To see more information about it . [Link](https://www.youtube.com/watch?v=uebQr2KvQzA)

### CRONTAB

A crontab file contains instructions to the cron(8) daemon of the general form: "run this command at this time on this date". Each user has their own crontab, and commands in any given crontab will be executed as the user who owns the crontab.

