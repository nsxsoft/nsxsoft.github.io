---
layout: post
title:  "How to Install Ansible on Windows!"
date:   2016-07-28 16:43:19 -0700
categories: ansible
---
Install cygwin from https://cygwin.com/install.html

Install the following packages:

- curl
- git
- python
- python-setuptools
- python-crypto
- openssl
- openssl-devel
- libffi-devel
- gcc-g++
- vim

Install pip
```
easy_install-2.7 pip
```

Install Ansible
```
pip install ansible
```
