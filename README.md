aws_backup_custom
=========

AWS backup custom role for trellis sites

Requirements
------------

ansible >= 2.9

Role Variables
--------------

These go into vault:
vault_aws_access_key_id,
vault_aws_secret_access_key

These go into trellis/group_vars/staging/main.yml: 
vault_aws_region,
aws_backup_db_name,
aws_backup_folder_path,
aws_bucket_name

This one goes into the role defaults/main.yml: 
include_web_folder


Dependencies
------------

None


License
-------

BSD

Author Information
------------------
by: armov
