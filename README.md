Python
=========
This install all dependent packages required for mysqlDB

Requirements
------------
debian/ubuntu

Role Variables
--------------
None

Dependencies
------------
None
Example Playbook
----------------

  name: Deploy a web application
  hosts: db_web_server_for_flask
  roles:
    - python
    - mysql_DBrole
    - flask_webrole