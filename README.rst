========================
Template website project
========================

This is a basic template web project with a development environment created
in a `Vagrant`_ virtual machine and provisioned by a `Ansible`_ playbooks.

The guest virtual development environment shares the src folder from the host
and serves the website mapped to port 8080 on the host.

The provisioning process downloads and extracts `Bootstrap`_ into the site's
stylesheets folder.


---------------
Getting Started
---------------

#. Install Ansible
#. Install Vagrant
#. cd dev-env
#. vagrant up
   Note: Default vagrant user password is blank (when prompted for sudo access

.. _`Vagrant`: http://www.vagrantup.com/
.. _`Ansible`: http://ansible.cc/
.. _`Bootstrap`: http://twitter.github.com/bootstrap/

