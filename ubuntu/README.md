<h1 align="center">Ubuntu Setup</h1>
<p align="center"><img src="../docs/ubuntu.png" alt="Systems"></p>

# Overview
A playbook for Ubuntu dev machine.  

# How to
## Install ansible
```shell
suto apt install ansible
``` 

## Run ansible
Please customize the contents of the playbook as you wish.
```shell
ansible-playbook playbook.yml -i inventory --ask-become-pass
``` 

## Additional installations
Please install the packages that are not available in ubuntu package manager.
- [Zoom](https://zoom.us/)
- [GVM](https://github.com/moovweb/gvm), or goenv
- [NVM](https://github.com/nvm-sh/nvm), or nodenv
- IDEs

## Reboot
Reboot the OS and you're done.  

