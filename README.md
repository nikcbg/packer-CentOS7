# packer-CentOS7

### CentOS 7 Minimal Packer config.json and kickstart file for building a vagrant virtualbox base box
### Kikckstart file is based off of https://www.centosblog.com/centos-7-minimal-kickstart-file/
----------------------------------------------------------------------------------------------------------------
### Requirements
- The following software must be installed on your local machine before you can use Packer to build the Vagrant box file:

- [Packer](http://www.packer.io/)
- [Vagrant](http://vagrantup.com/)
- [VirtualBox](https://www.virtualbox.org/)
----------------------------------------------------------------------------------------------------------------------------

### This repository contains template for CentOS7 x64 that can create Vagrant base box using Packer.

### Packer command
- `packer build centos7.json`

- This command creates the box for Vagrant.
------------------------------------------------------------------------------------------------------------------------
### Vagrant command
- vagrant box add "packer box name here"

- This add's the box created from the packer command into Vagrant's local store.

- `vagrant up`

Will start up the Centos7 box.
