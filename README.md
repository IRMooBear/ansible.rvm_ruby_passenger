RVM Ruby Passenger
=========
Compile the passenger dynamic module for nginx after rvm.ruby has installed ruby.

Requirements
------------
Ruby must be installed.  RVM must be installed.

Role Variables
--------------
Too many to list, see defaults/main.yml for anything ye wish to customize.

Dependencies
------------
    rvm.ruby
    
Example Playbook
----------------
Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: irmoobear.rvm_ruby_passenger }

License
-------
BSD

Author Information
------------------
An optional section for the role authors to include contact information, or a website (HTML is not allowed).