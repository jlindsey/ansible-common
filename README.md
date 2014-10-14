Ansible Common
==============
An ansible role for common ubuntu/debian server configuration.

Variables
---------
Role requires the following variables to be set in the group, playbook, etc.

- **login_user**: User to create for logins (other than ubuntu/root)
- **user_pass_shadow**: The [shadowed password][1] for the login user
- **user_public_key**: The public key string for the login user

[1]: http://en.wikipedia.org/wiki/Passwd#Shadow_file

License
-------
Copyright (c) 2014 Josh Lindsey. See [LICENSE](LICENSE) for details.
