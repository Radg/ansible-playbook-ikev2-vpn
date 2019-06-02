# Ansible playbook and role for set up IKEv2 VPN server for iOS / macOS

ikev2-vpn-server role and setupvpn_playbook sets up IKEv2 VPN server that serves iOS / macOS clients

## Requirements

Ubuntu 16.04 required

## Role Variables

network_interface - server's internet connected network interface

admin_email - email for certificate expiring notifications

## Example Playbook

  hosts: moscow
  
  become: yes

  roles:
  
    - ikev2-vpn-server

