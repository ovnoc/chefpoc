# Test Kitchen Setup

## download chefdk
https://downloads.chef.io/chefdk

sudo apt-get -y install virtualbox ruby-dev

sudo dpkg-reconfigure virtualbox-dkms
sudo dpkg-reconfigure virtualbox
sudo modprobe vboxdrv

## download vagrant
https://www.vagrantup.com/downloads.html

from repo root

```
$ kitchen list # shows your choices of VM's
$ kitchen create # downloads VM's
$ kitchen converge # test the STIG cookbook on Ubuntu
```
