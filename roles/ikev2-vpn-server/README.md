Role Name
=========

This role sets up IKEv2 VPN server that serves iOS / macOS clients

Requirements
------------

Ubuntu 16.04 required

Role Variables
--------------

network_interface - server's internet connected network interface
admin_email - email for certificate expiring notifications

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

  hosts: moscow
  become: yes

  roles:
    - ikev2-vpn-server

