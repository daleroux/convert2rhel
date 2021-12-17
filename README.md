# convert2rhel
Ansible playbook to convert a CentOS7 system to RHEL7
Compatible with ansible-2.9

## Support

This playbook is provided as is for educational purposes with no warranty.

## Before runnning the playbook

Take a snapshot (or backup) of the CentOS systems you intend to convert, before us.

## Variables

Modify the different variables so that it reflect your Satellite, organization and activation key.
Modify the inventory file with the hosts you intend to convert.
Modify the remote user in the ansible.cfg file, so that it reflects your environment

## Execution 

ansible-playbook convert.yml

## Author Information

This playbook was created in 2021 by Dan Leroux 
