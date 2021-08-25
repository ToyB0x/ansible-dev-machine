<h1 align="center">Mac Setup</h1>
<p align="center"><img src="../docs/mac.png" alt="Systems"></p>

# Overview
A playbook for Mac dev machine.  
(Single ansible file for readability)

# How to
## OS update
Please update Mac OS itself.

## Homebrew / Ansible installation
```shell
# Install homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# Install ansible
brew install ansible
``` 

## Run ansible
Please customize the contents of the playbook as you wish.
```shell
ansible-playbook playbook.yml -i inventory
``` 

## Additional installation of packages not compatible with Homebrew
- [Zoom](https://zoom.us/)
- [prezto](https://github.com/sorin-ionescu/prezto)
- [GVM](https://github.com/moovweb/gvm), or goenv
- [NVM](https://github.com/nvm-sh/nvm), or nodenv
- Xcode  

## Reboot
Reboot the OS and you're done.  
