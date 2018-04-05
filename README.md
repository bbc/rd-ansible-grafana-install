rd-ansible-grafana-install
=========

This module installs grafana and sets up a influxdb data source

Requirements
------------

This module requires Ansible 2.4

Role Variables
--------------

See defaults for variables and descriptions


Dependencies
------------

This role requires an influxdb data source

Example Playbook
----------------

Example to call:

    - hosts: all
      roles:
         - { role: rd-ansible-grafana-install }
