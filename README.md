# Vagrant - X Window Client

A Vagrant project to build a VM that can run application with GUI.

The VM is configured so that a X Window client application started there will connect to the X Window server running on the host.

## Prerequisites

* Install VirtualBox - [instructions](https://www.virtualbox.org/wiki/Downloads)
* Install Vagrant - [instructions](https://www.vagrantup.com/downloads.html)
* On MAC install X11 server - [xquartz](https://www.xquartz.org/)
* Enable the server to accept connections - run `xhost +`
* Test that the server works locally - run `xeyes`

## Run the project

* Create the VM - run `vagrant up`
* Login to VM - run `vagrant ssh`
* Run a GUI application e.g. `xeyes`