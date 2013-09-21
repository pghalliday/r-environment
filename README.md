r-environment
=============

Vagrant setup for the R programming language

Prerequisites
-------------

- [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](http://downloads.vagrantup.com/)
- [XQuartz](http://xquartz.macosforge.org/landing/) (on OSX) for X11 forwarding
- The Vagrant bindler plugin

```
vagrant plugin install bindler
vagrant bindler setup
```

- Other vagrant plugins

```
vagrant plugin bundle
```

Usage
-----

```
vagrant up
vagrant ssh
```

See Vagrant [documentation](http://docs.vagrantup.com/v2/) if you need to know more about Vagrant

License
-------

Copyright &copy; 2013 Peter Halliday  
Licensed under the MIT license.

