# vagrant-coreboot
This repository holds my own `Vagrantfile` templates for creating a VM suitable for building coreboot. That way, all the build tools are contained inside one environment.

The purpose of these templates is not to automate the building of coreboot, but to automate the building of a linux environment thats ready to build coreboot, assuming you have your coreboot sources under `./source`

Spin up the VM you want with `vagrant up`, log in with `vagrant ssh`, navigate to the `/source` folder and begin working away! 

I have the folder names in this repo ending in either `vbox` or `libvirt`, depending on which backend vagrant will use.
