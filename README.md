# ansible-fedora-workstation
This Ansible powered post-install playbook is intended for setting up a Fedora 26+ Workstation. 

## Quick setup
The Quick setup assumes that a regular user was created and it was granted with the administration role. 
```
$ sudo dnf install -y ansible
$ git clone https://github.com/mquintiliano/ansible-fedora-workstation.git
$ cd ~/ansible-fedora-workstation       # adjust it to the directory where you cloned the repo
$ ansible-playbook post-install.yml --ask-sudo-pass
```
