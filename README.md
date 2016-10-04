Ansible-Grafana
=========

Ansible role that install grafana from the Grafana apt repository.

Requirements
------------

No requirements.

Role Variables
--------------

No variables are being used for now. Role simply uses grafana from the apt-get repository and uses default settings.

There will be customization options in the future if needed.

Dependencies
------------

No dependencies.

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible-grafana

License
-------

MIT
