# How to setup your VPS using ansible

## Getting started
    
### Requirements:
* ansible >= 2.3 on the host machine (see more https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

### Launch the setup:
    $ ansible-playbook -u root --ask-pass -i "hosts" -l prod setupVPS.yml  --ssh-extra-args='-o StrictHostKeyChecking=no'