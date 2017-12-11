ansible-newsbeuter-spread
=========================

.. image:: http://img.shields.io/badge/ansible--galaxy-ansible-newsbeuter-spread-blue.svg
  :target: https://galaxy.ansible.com/narfman0/ansible-newsbeuter-spread/

.. image:: https://travis-ci.org/narfman0/ansible-newsbeuter-spread.png?branch=master
    :target: https://travis-ci.org/narfman0/ansible-newsbeuter-spread

Ansible role that installs and configures newsbeuter-spread_.

.. _newsbeuter-spread: https://github.com/narfman0/newsbeuter-spread/

We use gunicorn and supervisord

Installation
------------

Install with ```ansible-galaxy install narfman0.ansible-newsbeuter-spread``

Note: by default, the newsbeuter cache is expected to be in the home directory:
`/home/newsbeuter/.newsbeuter/cache.db`.

TODO
----

* Create virtual env

License
-------

Copyright (c) 2017 Jon Robison

See included LICENSE for licensing information
