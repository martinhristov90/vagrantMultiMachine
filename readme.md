## This repository provides a simple Vagrantfile to use with Vagrant, providing multi-machine setup.

## How to install Vagrant :

- Information about installing Vagrant can be found on the official HashiCorp website [here](https://www.vagrantup.com/docs/installation/)

## How to use it :

- In a directory of your choice,clone the github repository with 
`git clone https://github.com/martinhristov90/vagrantMultiMachine.git`
- Change into the directory using : `cd vagrantMultiMachine`
- Execute `vagrant up`
- It might take some time to download the boxes since you do not have them added to Vagrant.
- Check with `vagrant status` that you have both Vagrant boxes running. The output should look like this:
```shell

Current machine states:

web1                      running (virtualbox)
web2                      running (virtualbox)

This environment represents multiple VMs. The VMs are all listed
above with their current state. For more information about a specific
VM, run `vagrant status NAME`.

```

- To stop the running machines execute `vagrant halt`, to destroy the setup use `vagrant destroy`.
