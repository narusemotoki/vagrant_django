==============
Vagrant Django
==============

I often use Django on Vagrant. But set up is bit trouble. So this project is template of development Django on Vagrant.

You can get Django development environment easily.
You need install Vagrant and Ansible before using this project.

---------------
How to use this
---------------

::

    $ cd vagrant
    $ vagrant up
    $ vagrant ssh

Django application in /srv/server/djangoapp

------------------------------
What does this project set up?
------------------------------

* Python 3.4
* PostgreSQL 9.3
* Django 1.6.5 or later
* Nginx

This project is set up Python 3.4 from source code. It takes long time.

PostgreSQL
==========

::

    username: postgres
    password: postgres
    database: dev

Virtualenv
==========

::

    $ workon dev
