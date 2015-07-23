# [Ansible WebPlaybooks](https://galaxy.ansible.com/list#/roles/441)
[![npm version](https://img.shields.io/npm/v/ansible-web-playbooks.svg?style=flat)](https://www.npmjs.com/package/ansible-web-playbooks) [![build status](http://img.shields.io/travis/mgcrea/ansible-web-playbooks/master.svg?style=flat)](http://travis-ci.org/mgcrea/ansible-web-playbooks) [![npm downloads](https://img.shields.io/npm/dm/ansible-web-playbooks.svg?style=flat)](https://www.npmjs.com/package/ansible-web-playbooks) [![dependencies status](http://img.shields.io/david/mgcrea/ansible-web-playbooks.svg?style=flat)](https://david-dm.org/mgcrea/ansible-web-playbooks)

Set of playbook roles to orchestrate your web servers, powered by Ansible.

>
```
$ tree roles -L 2
roles
├── ansible
│   ├── accelerated
│   ├── facts
│   ├── fireball
│   └── setup
├── database
│   ├── beanstalkd
│   ├── mongodb
│   ├── mysql
│   └── redis
├── networking
│   ├── avahi
│   ├── btsync
│   ├── interfaces
│   ├── openvpn
│   ├── pptp
│   ├── transmission
│   └── x2go
├── system
│   ├── boot
│   ├── docker
│   ├── ssh
│   ├── sudo
│   └── vlc
└── web
    ├── apache2
    ├── iojs
    ├── nginx
    ├── nodejs
    ├── php5
    └── varnish
```


## Documentation and examples

+ Check the [galaxy role](https://galaxy.ansible.com/list#/roles/441) and [changelog](https://github.com/mgcrea/ansible-web-playbooks/releases).


## Quick start

+ You can run the playbooks with [Vagrant](http://www.vagrantup.com/)

>
    $ vagrant up
    $ ansible-playbook -i vagrant_inventory playbook.yml --tag apt_update,mongodb,nodejs


## Developers

Clone the repo, `git clone git://github.com/mgcrea/ansible-web-playbooks.git`, [download the latest release](https://github.com/mgcrea/ansible-web-playbooks/zipball/master) or install with npm `npm install ansible-web-playbooks`.

WebPlaybooks is tested with `vagrant` against the latest stable release of Ansible.

>
    $ vagrant up
    $ ansible-playbook -i vagrant_ansible_inventory_default playbook.yml


## Contributing

Please submit all pull requests the against master branch. Thanks!


## Authors

**Olivier Louvignes**

+ http://olouv.com
+ http://github.com/mgcrea


## Copyright and license

    The MIT License

    Copyright (c) 2013-2014 Olivier Louvignes

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in
    all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
    THE SOFTWARE.
