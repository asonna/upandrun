# upandrun #

A very simple vagrant environment for getting up and running with Puppet Enterprise. 

This repo provides you with a complete, yet simple environment that consists of a master (CentOS7), as well as a Linux (CentOS7) and Windows VM. 

## Pre-Steps ##

Before cloning this repo, you'll have to install both [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads). 

For downloads : https://puppet.com/download-puppet-enterprise/thank-you

Once both are installed, you'll be able to do the following steps from your CLI:

```
'git clone https://github.com/Grace-Andrews/upandrun'

'cd upandrun'

**vagrant up each vm separately, wait for the previous vm to load fully before bringing up the next one** 

'vagrant up /master/'

'vagrant up /linux/'

'vagrant up /windows/'

'vagrant hosts list'

'vagrant ssh <IPaddress for Master>'
```

In order to get into your boxes, you can either ssh in from your command line, or you can use the VirtualBox interface.
