# 1
- controller: Ubuntu 18.04 on WSL (Windows 10 Home)
- remote: Raspbian Buster Lite
    - https://downloads.raspberrypi.org/raspbian_lite/images/raspbian_lite-2020-02-07/2020-02-05-raspbian-buster-lite.zip

# 2
1. Install ansible
    - https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#installing-ansible-on-debian

2. Install dependencies
```
$ ansible --version
ansible 2.9.4
  config file = /etc/ansible/ansible.cfg
  configured module search path = [u'/home/c/.ansible/plugins/modules', u'/usr/share/ansible/plugins/modules']
  ansible python module location = /usr/lib/python2.7/dist-packages/ansible
  executable location = /usr/bin/ansible
  python version = 2.7.17 (default, Nov  7 2019, 10:07:09) [GCC 7.4.0]
$ ansible-galaxy list
# /home/c/.ansible/roles
- geerlingguy.docker, 2.6.0
- geerlingguy.pip, 1.3.0
```
