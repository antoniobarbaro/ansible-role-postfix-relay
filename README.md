postfix-relay
=============

Configure postfix for relaying emails

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Example amazon ses postifix relay configuration

    - hosts: servers
      vars:
        postfix_relay_host: email-smtp.eu-west-1.amazonaws.com
        postfix_relay_port: 587
        postfix_relay_username: xxxxxxxxxxxx
        postfix_relay_password: xxxxxxxxxxxxxxxxxxxxx
      roles:
         - postfix-relay

License
-------

BSD

Author Information
------------------

Antonio Barbaro <antonio.barbaro@gmail.com>
