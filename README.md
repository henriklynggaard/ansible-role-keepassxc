KeepassXC
=========

Installs keepassxc (https://keepassxc.org/) using the debian packages posted here: https://github.com/magkopian/keepassxc-debian/releases


Requirements
------------

None

Role Variables
--------------

    keepass_version: 2.1.4-1/keepassxc_2.1.4-1_amd64_stable.deb
    keepass_url: "https://github.com/magkopian/keepassxc-debian/releases/download/{{keepass_version}}/keepassxc_{{keepass_version}}_amd64_stable.deb"

Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      connection: local
    
    roles:
      - henriklyngaard.keepassxc
      
      
License
-------

MIT



