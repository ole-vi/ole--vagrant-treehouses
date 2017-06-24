# ole--vagrant-treehouses

This is the first iteration of the VM with [treehouse-builder](https://github.com/ole-vi/treehouse-builder) to enable Raspberry Pi image customization on non-Linux systems.

## Instructions

### Prerequisites

 * 8GB of available disk space
 * `4`GB RAM
 * Vagrant

### Getting Started

```
git clone https://github.com/ole-vi/ole--vagrant-treehouses.git
cd ole--vagrant-treehouses
vagrant up
vagrant ssh
```

### To view building process messages

```
screen -x
```
### The new image will be created in the `image` directory

## Built with

* [Vagrant](https://www.vagrantup.com)
* [VirtualBox](https://www.virtualbox.org)
* [treehouse-builder](https://github.com/ole-vi/treehouse-builder)