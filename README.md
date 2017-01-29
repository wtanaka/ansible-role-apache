[![Build Status](https://travis-ci.org/wtanaka/ansible-role-apache.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-apache)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-apache.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-apache)

wtanaka.apache
==============

This ansible role installs Apache 2.x and allows you to specify which
apache modules to enable

Example Playbook
----------------

    - hosts: all
      roles:
      - role: wtanaka.apache
        # These variables can go either here or in the appropriate
        # host_vars or group_vars file

        # List of apache modules to enable
        apache_mods_enabled:
        - rewrite
        apache_mods_disabled:
        - proxy_fcgi


License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
