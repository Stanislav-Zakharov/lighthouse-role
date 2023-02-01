Role Name
=========

Lighthouse installation role

Role Variables
--------------

|Variable| Description|Default value|
|---|---|---|
|nginx_user_name|Nginx user name|nobody|
|lighthouse_vcs|Lighthouse github repository link|https://github.com/VKCOM/lighthouse.git|
|lighthouse_location_dir| Installation dir | /var/lib/lighthouse|


Dependencies
------------

* nginxinc.nginx


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - lighthouse-role

License
-------

MIT

