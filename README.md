Ubuntu based Developer Machine
======================

## Install required roles.
`sudo ansible-galaxy install -r provisioning/requirements.yml --force`

## Prerequisites

- Copy custom.config.yml to config.yml and replace necessary values
- Your system should have python-netaddr installed (`sudo apt-get install python-netaddr`)

## Use

- `ansible-playbook -i hosts provisioning/playbook.yml`

## Includes:

- git
- ansible
- vagrant
- virtualbox
- nvm
- rvm
- drush
- terminus
- mysql-client
- atom
- keepassx
- chrome
- slack
- dropbox
- spotify
