vector
=========

This role installs [vector](https://github.com/vectordotdev/vector)

Role Variables
--------------

| Name           | Default Value | Description                        |
| -------------- | ------------- | -----------------------------------|
| vector_version_major | 0.27.0 | Vector major version |

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: vector }

License
-------

MIT

Author Information
------------------

Petr Losev  
wowpetr@gmail.com