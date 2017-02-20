Provisioning for new site
==========================

## Requirements

* nginx
* Python 3.4
* Git
* pip
* virtuanenv(wrapper)
* systemd

Installation:

    sudo add-apt-repository ppa:fkrull/deadsnakes
    sudo apt update
    sudo apt install nginx git python3.4 python3-pip
    sudo pip3 install virtualenvwrapper

## Nginx Virtual Host & Systemd Conf.

* nginx.template.conf, gunicorn-systemd.template.service
* SITENAME replace to YOUR SITENAME

## Virtualenvwrapper Conf.

    export VIRTUALENVWRAPPER_PYTHON=/usr/bin/PYTHON
    export WORKON_HOME=~/.envs
    source /usr/local/bin/virtualenvwrapper.sh
