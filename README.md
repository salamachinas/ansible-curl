ansible-curl
============

This role installs curl

[![Ansible Galaxy](https://img.shields.io/ansible/role/14811.svg)](https://galaxy.ansible.com/salamachinas/curl/)

Requirements
------------

This role requires Ansible 2.0 or higher and platform requirements are listed
in the metadata file.

Install
-------

```sh
ansible-galaxy install salamachinas.curl
```

Tests
-----

```sh
docker build -t test-ansible-curl-centos7 -f tests/Dockerfile_centos7 --force-rm .
docker build -t test-ansible-curl-debian7 -f tests/Dockerfile_debian7 --force-rm .
docker build -t test-ansible-curl-debian8 -f tests/Dockerfile_debian8 --force-rm .
docker build -t test-ansible-curl-ubuntu14 -f tests/Dockerfile_ubuntu14 --force-rm .
docker build -t test-ansible-curl-ubuntu16 -f tests/Dockerfile_ubuntu16 --force-rm .
```
