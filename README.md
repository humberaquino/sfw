What is sfw?
===========

sfw stands for "simple firewall". The main objective is to have a project simple enough to understand and adapt it to someone needs. 

Other goals are:

- Everything under the same directory when possible: For simple projects I like the simplicity of having all configuration files unther the same parent directory.
- One script to generate IPv4 rules and other for IPv6
- Be able to save and restore rules
- Disable firewall action 
- Verbose status 
- Simple enough to be used as a learning tool

Installation
============

- Clone repository in a directory. E.g. /etc/sfw
- Create a symbolic link
sudo ln -sf /etc/sfw/lib/sfwctl /etc/init.d/sfw


Configuration
=============

TODO

Usage
=====

See help
   /etc/init.d/sfw help

More TODO
====

- Create CHANGELOg file
- Improve this README file