# GromacsTemplateBuilder
Build Ubuntu template with Gromacs by [packer](https://www.packer.io/).

# Prerequisites
- Install Packer by following the official guide at https://learn.hashicorp.com/tutorials/packer/getting-started-install 
- Install VMware Fusion or Workstation or Player for your OS if you want to use vmware-iso as builder, or figure out the vCenter/ESXi URL/username/password if you want to use vsphere-iso as builder. 
- Clone this repo to your local folder

# Commands to build the template
In the console, run the following command. 
```
packer build ubuntu-20.04-local.json
```

# Todo:
- [x] Build Ubuntu 20.04 locally
- [x] Install CUDA and other dependencies in the template
- [x] Install Gromacs 2020.4 in the template 