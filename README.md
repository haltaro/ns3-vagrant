# Vagrant for ns-3.27

This is a Vagrantfile for generating ns-3.26 environment on Ubuntu 16.04.

## Requirement

Install VirtualBox and Vagrant on a host computer.

## Install

Clone this repo to wherever you like. And type the following command.

```
vagrant up
```

Vagrant helps us to provision ns-3.27 environment:

- Install dependent packages
- Install ns-3.27
- Compile
- Test

(It will take a while...)

Then you can use ns-3.27 on the virtual machine via ssh by using the following command.

```
vagrant ssh
```

## Special thanks

The Vagrantfile is based on [diogomg/vagrant-ns-3-setup](https://github.com/diogomg/vagrant-ns-3-setup). I modified some lines to adapt the file to ns-3.27. 

