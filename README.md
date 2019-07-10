Debug Dump All Vars
===================

[![Build Status](https://travis-ci.org/ome/ansible-role-debug-dumpallvars.svg)](https://travis-ci.org/ome/ansible-role-debug-dumpallvars)
[![Ansible Role](https://img.shields.io/ansible/role/41958.svg)](https://galaxy.ansible.com/ome/debug_dumpallvars/)

Dump all variables to a file on the remote host.

This may be useful when debugging Ansible roles. Most Ansible variables will be written to a file on the remote host.


Role Variables
--------------

Optional variables:

- `debug_dumpallvars_file`: The file to write the variables to, default `/tmp/ansible-debug-dumpallvars.txt`.


Example Playbook
----------------

    - hosts: localhost
      roles:
      - role: ome.debug_dumpallvars
        debug_dumpallvars_file: /tmp/ansible-dumpvars.txt


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
