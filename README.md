# born2beroot
This document is a System Administration related exercise.

![imagen](https://upload.wikimedia.org/wikipedia/commons/7/78/Debian_logo_redeploiement.png)

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
