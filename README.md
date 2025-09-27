Portainer and Portainer Agent
=========

Deploy either Portainer or the Portainer Agent in Docker.

Requirements
------------

Docker must already be installed.

Role Variables
--------------

| Name                         | Comment                                                   | Default value  |
|------------------------------|-----------------------------------------------------------|----------------|
| portainer        | Either "portainer" or "agent" to define which to deploy.                         | ``      |
| portainer_data_dir | Directory where the portainer or portainer-agent folder will be created. | `/data` |

Dependencies
------------



Example Playbook
----------------

  ```
  ---
  - name: Portainer and portainer-agent setup
    hosts: all
    roles:
      - role: role-portainer
  ```


License
-------

BSD
