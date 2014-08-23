osx-node.js
===========

An Ansible role to setup node.js on OS X

Requirements
------------

[Homebrew](http://brew.sh/) must be installed.

Role Variables
--------------

osx_node_global_packages:
  - grunt-cli
  - gulp
  - webpack

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - hnakamur.osx-node.js

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
