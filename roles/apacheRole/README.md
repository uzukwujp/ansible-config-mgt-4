Apachesetup
=========
apache
Setting httpd webservers such that it should be used by the load balancer 
Requirements
------------

Pre-requistic - before running the role you have to create the .yml file and import the role as well as hosts, if you are using group name in host then first create it, in inventory file

Role Variables
--------------

No variables are used 

Dependencies
------------

This role can be used as a setup of apache webserver, and also can be used for the purpose of load balancer- for this you have to install role loadbalancer

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: myservers
      roles:
         - role: "apache"

License
-------

BSD

Author Information
------------------

For Any Queries contact me on limkedIn:
https://www.linkedin.com/in/gautam-khatri-8891b3127/
