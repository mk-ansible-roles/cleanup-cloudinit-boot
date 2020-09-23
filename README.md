cleanup-cloudinit-boot
=======================

This role removes the cloud-init package from RHEL/Fedora systems to avoid changes after poweroff/reboot in RHV. It also removes localhost IP adresses from /etc/hosts that reference the FQDN or hostname


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: cleanup-cloudinit-boot }

License
-------

GPL v3

Author Information
------------------

Markus Koch
Please leave comments in the issue list
