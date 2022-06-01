ansible-docker
=========

This role permit to deploy the latest version of docker on any GNU/Linux based Operating System.

Requirements
------------

Role Variables
--------------

|| Variables | type | Descriptions | Defaults |
|-|-|-|-|-|
||`docker_compose` |`bool`| Install docker-compose packahes as addon |`true`|
||`reset_before`|`bool`| Reset all docker installations befor start new docker packages installation. |`true`|

Dependencies
------------

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Wilfried KOUASSI:sunglasses: <Sysops:computer: && Devops:keyboard: && Cloud engineer:computer_mouse:>
