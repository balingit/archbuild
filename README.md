# archbuild
After the initial archlinux install, and the setup of ssh, sudo, an admin user and the install of ansible-core, the site. yml playbook will install and configure a usable desktop environment.

## Prerequisites
A requirements.yml must be installed using ansible-galaxy. Example:

 sudo ansible-galaxy collection install -r requirements.yml -p /usr/share/ansible/collections
