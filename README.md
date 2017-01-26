Ubuntu based Developer Machine
======================

## Install required roles.
`sudo ansible-galaxy install -r provisioning/requirements.yml --force`

## Prerequisites

- Copy custom.config.yml to config.yml and replace necessary values
- Your system should have python-netaddr installed (`sudo apt-get install python-netaddr`)

## Includes:

- git
- ansible
- vagrant
- virtualbox
- nvm
- rvm
- drush
- mysql-client
- atom
- keepassx
- chrome
- slack
