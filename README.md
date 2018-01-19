ec2_asg
=======

Role to set up a Launch Configuration and Autoscaling Group

Requirements
------------

Role Variables
--------------

* `ec2_asg_security_groups` - a list of security group names or IDs for the launch configuration
* `ec2_asg_security_group_filters` - a list of filters to use to find one or more security groups
* `ec2_asg_remove_timeout` - timeout length when removing an ASG. Defaults to 600

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

XVT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
