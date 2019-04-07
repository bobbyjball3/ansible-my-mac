# Ansible Playbook for Post-wip MacOS Setup

## What it does
- Installs [Brew](https://docs.brew.sh/)
- Installs [Oh My ZSH](https://github.com/robbyrussell/oh-my-zsh)
- Installs [PowerLevel9K](https://github.com/bhilburn/powerlevel9k)
- Installs a set of [useful formulae](hostvars/localhost#L10-L16)
- Installs a set of [useful casks](hostvars/localhost#L1-L8)
- Disables natural scrolling
- Enable tap to click (left and right click)

## How to use it
_note_: Requres you have sudo as root to set some settings
1. Once you've satisfied all of the requirements listed in the Requirements section, execute the following

```Shell
ansible-playbook -K playbook.yml
```

## Requirements
- Must be an administrator on the Mac
- Python 2.7 or > 3.5 w/ pip
- [Ansible](https://docs.ansible.com/ansible/2.4/intro_installation.html#latest-releases-via-pip) >= v2.4.x
