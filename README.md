# Ansible Kontena Server

<br />

<p align="center">
    <a href="https://kontena.io/">
        <img src="https://kontena.io/images/kontena-logo.svg" width="280">
    </a>
</p>

<br />
<br />

[![Build Status](https://travis-ci.org/roquie/ansible-kontena-server.svg?branch=master)](https://travis-ci.org/roquie/ansible-kontena-server)

Ansible role to install Kontena Server on Masters.

Example, how to use, can be found at `tests` directory.


## Install

```
ansible-galaxy install roquie.ansible-kontena-server
```

## TODO

* [ ] Full idempotence

## Supported OS

For now supports:
* Ubuntu 16.04 LTS
* Ubuntu 14.04 LTS

## Vagrant

* `cd /path/to/project`
* `cd tests && ansible-galaxy install -r requirements.yml && cd ..`
* `vagrant up` 

### Warning
    
If u want rename project, make sure to rename role (`ansible-kontena-server`) inside `tests/playbooks/vagrant.yml`.


## License

MIT
