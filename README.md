# ole--vagrant-treehouses

This is the first iteration of the VM with [treehouse-builder](https://github.com/ole-vi/treehouse-builder) to enable Raspberry Pi image customization on non-Linux systems.

## Instructions

### Prerequisites

 * 8GB of available disk space
 * 4GB RAM
 * Vagrant
 * VirtualBox

### Getting Started

```
git clone https://github.com/ole-vi/ole--vagrant-treehouses.git
cd ole--vagrant-treehouses
vagrant up
```


### Retrieve builds

When you are done making your image power off the virtual machine. Once the machine is powered off, head over to the `treehouse-builder/images` directory. There should be a few files in that directory. The .zip file is the unmodified base image, which is downloaded by the script when executed. The .img file is the new customized image and is now ready to be burned onto the microSD card.

### To view building process messages

```
vagrant ssh
screen -x
```
Note: The new image will be created in the `image` directory

## Built with

* [Vagrant](https://www.vagrantup.com)
* [VirtualBox](https://www.virtualbox.org)
* [treehouse-builder](https://github.com/ole-vi/treehouse-builder)
