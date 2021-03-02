Yum_offline_installer
=========

It's role for offline installation RPM-packages from ./files/{{ pack }}

Supported OS
------------

- CentOS 7
- RHEL 7
- Oracle Linux 7

Requirements
------------

Place your RPM-packages in ./files/{{ pack }}
Directory {{ pack }} have been created manually

Role Variables
--------------

* `pack` - name of directory in ./files where have been placed RPM-packages


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - yum_offline_installer
      vars:
        pack: java

License
-------

BSD

Author Information
------------------

TG: @Kolyunya_the_best
