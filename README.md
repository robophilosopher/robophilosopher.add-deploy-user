robophilosopher.add-deploy-user
=========

This role captures the user setup found in [My First 10 Minutes On a Server - Primer for Securing Ubuntu](http://www.codelitt.com/blog/my-first-10-minutes-on-a-server-primer-for-securing-ubuntu/)

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------
It's expected that you'll supply strong SHA512-crypted passwords to `crypted_deploy_password` and `crypted_root_password`. It's not a bad idea to use a password generator to create something strong. Then, you can use something like Python's crypt module to encrypt it.

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
# robophilosopher.add-deploy-user
