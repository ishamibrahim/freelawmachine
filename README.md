Free Law (Virtual) Machine
==========================

This project is designed to provide automation around building a ready-to-run
development environment for the (Free Law Project)[https://github.com/freelawproject]
using Vagrant boxes.

Hopefully, it will do away with the manual process described (here)
[https://github.com/freelawproject/courtlistener/wiki/Installing-CourtListener-on-Ubuntu-Linux]
and make having a dev environment as easy as `vagrant up`.

## Various Details
* Based on Ubuntu Server 32-bit (for now) 14.04 LTS
* Trying to target dev machines that have:
** 8 GB RAM
** Virtualbox (maybe add VMWare later but that may involve $$)
** Lack of VT-X support (hence 32-bit VM is the initial goal)

## References
[A packer template for Vagrant from Hashicorp](https://github.com/hashicorp/atlas-packer-vagrant-tutorial.git)
