# GromacsTemplateBuilder
Build Ubuntu templates with [packer](https://www.packer.io/).
Fill in server configuration in `json` files.
```
packer build ubuntu-16.04.json
packer build ubuntu-20.04.json
packer build ubuntu-20.04-local.json
```
Todo:
- [x] Build Ubuntu 20.04 locally
- [x] Build Ubuntu 16.04 on ESXi/vCenter server
- [ ] Build Ubuntu 18.04 locally or on server
- [ ] Install Gromacs 2020.4 in the template 