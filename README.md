ucf.ansible_role_lsb_core
=========

Installs lsb core package on RHEL / CentOS 7 / Amazon Linux 2 and re-runs ansible `setup` module so that ansible lsb facts are gathered.  

About LSB:<br>
Linux Standards Base (LSB) provides a set of standards that increases compatibility among Linux distributions. The redhat-lsb packages provide utilities needed for LSB compliant applications. It also contains requirements that ensure that all components required by LSB are installed on the system. 

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ucf.ucf.ansible_role_lsb_core }

License
-------

[MIT License](https://github.com/UCF/ansible-role-lsb-core/blob/master/LICENSE)

Author Information
------------------

Author(s): [Derek J. Bernard](https://github.com/derekjbernard), [Vinnie Vu](https://github.com/vinhtvu2)
