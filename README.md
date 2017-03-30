Ansible role: Composer
=========

Installs dependency manager for PHP.

Requirements
------------

None.

Role Variables
--------------

    composer_phar_url: http://getcomposer.org/composer.phar
    composer_bin_path: /usr/local/bin/composer

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.composer }

License
-------

MIT

Author Information
------------------
